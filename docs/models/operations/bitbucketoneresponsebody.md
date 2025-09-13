# BitbucketOneResponseBody

Successful response

## Example Usage

```typescript
import { BitbucketOneResponseBody } from "dokploy-sdk/models/operations";

let value: BitbucketOneResponseBody = {
  bitbucketId: "<id>",
  bitbucketUsername: null,
  appPassword: "<value>",
  bitbucketWorkspaceName: "<value>",
  gitProviderId: "<id>",
  gitProvider: {
    gitProviderId: "<id>",
    name: "<value>",
    providerType: "bitbucket",
    createdAt: "1711662589864",
    organizationId: "<id>",
    userId: "<id>",
  },
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `bitbucketId`                                                                            | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `bitbucketUsername`                                                                      | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `appPassword`                                                                            | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `bitbucketWorkspaceName`                                                                 | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `gitProviderId`                                                                          | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `gitProvider`                                                                            | [operations.BitbucketOneGitProvider](../../models/operations/bitbucketonegitprovider.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |