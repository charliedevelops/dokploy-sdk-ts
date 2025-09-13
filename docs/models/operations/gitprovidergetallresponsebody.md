# GitProviderGetAllResponseBody

## Example Usage

```typescript
import { GitProviderGetAllResponseBody } from "dokploy-sdk/models/operations";

let value: GitProviderGetAllResponseBody = {
  bitbucket: {
    appPassword: "<value>",
    bitbucketId: "<id>",
    bitbucketUsername: "<value>",
    bitbucketWorkspaceName: "<value>",
    gitProviderId: "<id>",
  },
  createdAt: "1717694387124",
  gitProviderId: "<id>",
  gitea: {
    accessToken: "<value>",
    clientId: "<id>",
    clientSecret: "<value>",
    expiresAt: 8752.72,
    gitProviderId: "<id>",
    giteaId: "<id>",
    giteaUrl: "https://flustered-horde.com",
    lastAuthenticatedAt: 3958.19,
    redirectUri: "https://orderly-pigpen.com/",
    refreshToken: "<value>",
    scopes: null,
  },
  github: null,
  gitlab: null,
  name: "<value>",
  organizationId: "<id>",
  providerType: "gitlab",
  userId: "<id>",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `bitbucket`                                                                                          | [operations.GitProviderGetAllBitbucket](../../models/operations/gitprovidergetallbitbucket.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `gitProviderId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `gitea`                                                                                              | [operations.GitProviderGetAllGitea](../../models/operations/gitprovidergetallgitea.md)               | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `github`                                                                                             | [operations.GitProviderGetAllGithub](../../models/operations/gitprovidergetallgithub.md)             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `gitlab`                                                                                             | [operations.GitProviderGetAllGitlab](../../models/operations/gitprovidergetallgitlab.md)             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `organizationId`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `providerType`                                                                                       | [operations.GitProviderGetAllProviderType](../../models/operations/gitprovidergetallprovidertype.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `userId`                                                                                             | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |