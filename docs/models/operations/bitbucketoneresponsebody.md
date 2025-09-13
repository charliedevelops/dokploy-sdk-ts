# BitbucketOneResponseBody

Successful response

## Example Usage

```typescript
import { BitbucketOneResponseBody } from "dokploy-sdk/models/operations";

let value: BitbucketOneResponseBody = {
  appPassword: null,
  bitbucketId: "<id>",
  bitbucketUsername: "<value>",
  bitbucketWorkspaceName: "<value>",
  gitProvider: {
    createdAt: "1721501526007",
    gitProviderId: "<id>",
    name: "<value>",
    organizationId: "<id>",
    providerType: "github",
    userId: "<id>",
  },
  gitProviderId: "<id>",
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `appPassword`                                                                            | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `bitbucketId`                                                                            | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `bitbucketUsername`                                                                      | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `bitbucketWorkspaceName`                                                                 | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `gitProvider`                                                                            | [operations.BitbucketOneGitProvider](../../models/operations/bitbucketonegitprovider.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `gitProviderId`                                                                          | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |