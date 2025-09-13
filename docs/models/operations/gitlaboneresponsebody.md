# GitlabOneResponseBody

Successful response

## Example Usage

```typescript
import { GitlabOneResponseBody } from "dokploy-sdk/models/operations";

let value: GitlabOneResponseBody = {
  gitlabId: "<id>",
  gitlabUrl: "https://spotless-flat.biz/",
  applicationId: "<id>",
  redirectUri: "https://fortunate-castanet.org",
  secret: "<value>",
  accessToken: "<value>",
  refreshToken: "<value>",
  groupName: "<value>",
  expiresAt: 1291.78,
  gitProviderId: "<id>",
  gitProvider: {
    gitProviderId: "<id>",
    name: "<value>",
    providerType: "bitbucket",
    createdAt: "1711072502659",
    organizationId: "<id>",
    userId: "<id>",
  },
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `gitlabId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitlabUrl`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `applicationId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `redirectUri`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `secret`                                                                           | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `accessToken`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `refreshToken`                                                                     | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `groupName`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `expiresAt`                                                                        | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitProviderId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitProvider`                                                                      | [operations.GitlabOneGitProvider](../../models/operations/gitlabonegitprovider.md) | :heavy_check_mark:                                                                 | N/A                                                                                |