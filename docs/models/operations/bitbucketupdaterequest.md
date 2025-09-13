# BitbucketUpdateRequest

## Example Usage

```typescript
import { BitbucketUpdateRequest } from "dokploy-sdk/models/operations";

let value: BitbucketUpdateRequest = {
  bitbucketId: "<id>",
  gitProviderId: "<id>",
  name: "<value>",
};
```

## Fields

| Field                    | Type                     | Required                 | Description              |
| ------------------------ | ------------------------ | ------------------------ | ------------------------ |
| `bitbucketId`            | *string*                 | :heavy_check_mark:       | N/A                      |
| `bitbucketUsername`      | *string*                 | :heavy_minus_sign:       | N/A                      |
| `appPassword`            | *string*                 | :heavy_minus_sign:       | N/A                      |
| `bitbucketWorkspaceName` | *string*                 | :heavy_minus_sign:       | N/A                      |
| `gitProviderId`          | *string*                 | :heavy_check_mark:       | N/A                      |
| `name`                   | *string*                 | :heavy_check_mark:       | N/A                      |
| `organizationId`         | *string*                 | :heavy_minus_sign:       | N/A                      |