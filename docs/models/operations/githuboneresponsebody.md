# GithubOneResponseBody

Successful response

## Example Usage

```typescript
import { GithubOneResponseBody } from "dokploy-sdk/models/operations";

let value: GithubOneResponseBody = {
  githubId: "<id>",
  githubAppName: "<value>",
  githubAppId: 3007.11,
  githubClientId: "<id>",
  githubClientSecret: "<value>",
  githubInstallationId: "<id>",
  githubPrivateKey: "<value>",
  githubWebhookSecret: null,
  gitProviderId: "<id>",
  gitProvider: {
    gitProviderId: "<id>",
    name: "<value>",
    providerType: "gitea",
    createdAt: "1718748169910",
    organizationId: "<id>",
    userId: "<id>",
  },
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `githubId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubAppName`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubAppId`                                                                      | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubClientId`                                                                   | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubClientSecret`                                                               | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubInstallationId`                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubPrivateKey`                                                                 | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `githubWebhookSecret`                                                              | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitProviderId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitProvider`                                                                      | [operations.GithubOneGitProvider](../../models/operations/githubonegitprovider.md) | :heavy_check_mark:                                                                 | N/A                                                                                |