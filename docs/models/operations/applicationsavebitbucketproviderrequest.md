# ApplicationSaveBitbucketProviderRequest

## Example Usage

```typescript
import { ApplicationSaveBitbucketProviderRequest } from "dokploy-sdk/models/operations";

let value: ApplicationSaveBitbucketProviderRequest = {
  applicationId: "<id>",
  bitbucketBranch: "<value>",
  bitbucketBuildPath: null,
  bitbucketId: "<id>",
  bitbucketOwner: "<value>",
  bitbucketRepository: "<value>",
  enableSubmodules: false,
};
```

## Fields

| Field                 | Type                  | Required              | Description           |
| --------------------- | --------------------- | --------------------- | --------------------- |
| `applicationId`       | *string*              | :heavy_check_mark:    | N/A                   |
| `bitbucketBranch`     | *string*              | :heavy_check_mark:    | N/A                   |
| `bitbucketBuildPath`  | *string*              | :heavy_check_mark:    | N/A                   |
| `bitbucketId`         | *string*              | :heavy_check_mark:    | N/A                   |
| `bitbucketOwner`      | *string*              | :heavy_check_mark:    | N/A                   |
| `bitbucketRepository` | *string*              | :heavy_check_mark:    | N/A                   |
| `enableSubmodules`    | *boolean*             | :heavy_check_mark:    | N/A                   |
| `watchPaths`          | *string*[]            | :heavy_minus_sign:    | N/A                   |