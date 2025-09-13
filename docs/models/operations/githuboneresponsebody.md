# GithubOneResponseBody

Successful response

## Example Usage

```typescript
import { GithubOneResponseBody } from "dokploy-sdk/models/operations";

let value: GithubOneResponseBody = {
  gitProvider: {
    createdAt: "1728958456876",
    gitProviderId: "<id>",
    name: "<value>",
    organizationId: "<id>",
    providerType: "gitea",
    userId: "<id>",
  },
  gitProviderId: "<id>",
  githubAppId: 8477.66,
  githubAppName: "<value>",
  githubClientId: "<id>",
  githubClientSecret: "<value>",
  githubId: "<id>",
  githubInstallationId: null,
  githubPrivateKey: "<value>",
  githubWebhookSecret: "<value>",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `gitProvider`                                                                      | [operations.GithubOneGitProvider](../../models/operations/githubonegitprovider.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitProviderId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubAppId`                                                                      | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubAppName`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubClientId`                                                                   | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubClientSecret`                                                               | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubInstallationId`                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubPrivateKey`                                                                 | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubWebhookSecret`                                                              | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |