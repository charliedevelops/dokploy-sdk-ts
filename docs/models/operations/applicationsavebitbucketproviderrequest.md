# ApplicationSaveBitbucketProviderRequest

## Example Usage

```typescript
import { ApplicationSaveBitbucketProviderRequest } from "dokploy-sdk/models/operations";

let value: ApplicationSaveBitbucketProviderRequest = {
  bitbucketBranch: "<value>",
  bitbucketBuildPath: null,
  bitbucketOwner: "<value>",
  bitbucketRepository: "<value>",
  bitbucketId: "<id>",
  applicationId: "<id>",
  enableSubmodules: false,
};
```

## Fields

| Field                 | Type                  | Required              | Description           |
| --------------------- | --------------------- | --------------------- | --------------------- |
| `bitbucketBranch`     | *string*              | :heavy_check_mark:    | N/A                   |
| `bitbucketBuildPath`  | *string*              | :heavy_check_mark:    | N/A                   |
| `bitbucketOwner`      | *string*              | :heavy_check_mark:    | N/A                   |
| `bitbucketRepository` | *string*              | :heavy_check_mark:    | N/A                   |
| `bitbucketId`         | *string*              | :heavy_check_mark:    | N/A                   |
| `applicationId`       | *string*              | :heavy_check_mark:    | N/A                   |
| `watchPaths`          | *string*[]            | :heavy_minus_sign:    | N/A                   |
| `enableSubmodules`    | *boolean*             | :heavy_check_mark:    | N/A                   |