# GitlabOneResponseBody

Successful response

## Example Usage

```typescript
import { GitlabOneResponseBody } from "dokploy-sdk/models/operations";

let value: GitlabOneResponseBody = {
  accessToken: "<value>",
  applicationId: "<id>",
  expiresAt: 1894.32,
  gitProvider: {
    createdAt: "1718061385664",
    gitProviderId: "<id>",
    name: "<value>",
    organizationId: "<id>",
    providerType: "gitea",
    userId: "<id>",
  },
  gitProviderId: "<id>",
  gitlabId: "<id>",
  gitlabUrl: "https://fortunate-castanet.org",
  groupName: "<value>",
  redirectUri: "https://favorable-subexpression.com",
  refreshToken: "<value>",
  secret: "<value>",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `accessToken`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `applicationId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `expiresAt`                                                                        | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitProvider`                                                                      | [operations.GitlabOneGitProvider](../../models/operations/gitlabonegitprovider.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitProviderId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitlabId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitlabUrl`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `groupName`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `redirectUri`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `refreshToken`                                                                     | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `secret`                                                                           | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |