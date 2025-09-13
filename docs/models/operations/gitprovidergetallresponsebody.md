# GitProviderGetAllResponseBody

## Example Usage

```typescript
import { GitProviderGetAllResponseBody } from "dokploy-sdk/models/operations";

let value: GitProviderGetAllResponseBody = {
  gitProviderId: "<id>",
  name: "<value>",
  providerType: "gitea",
  createdAt: "1725687930153",
  organizationId: "<id>",
  userId: "<id>",
  gitlab: {
    gitlabId: "<id>",
    gitlabUrl: "https://internal-schedule.org",
    applicationId: "<id>",
    redirectUri: "https://twin-presume.biz",
    secret: "<value>",
    accessToken: "<value>",
    refreshToken: "<value>",
    groupName: "<value>",
    expiresAt: 1740.43,
    gitProviderId: "<id>",
  },
  bitbucket: {
    bitbucketId: "<id>",
    bitbucketUsername: "<value>",
    appPassword: "<value>",
    bitbucketWorkspaceName: "<value>",
    gitProviderId: "<id>",
  },
  github: null,
  gitea: null,
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `gitProviderId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `name`                                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `providerType`                                                                                       | [operations.GitProviderGetAllProviderType](../../models/operations/gitprovidergetallprovidertype.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `organizationId`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `userId`                                                                                             | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `gitlab`                                                                                             | [operations.GitProviderGetAllGitlab](../../models/operations/gitprovidergetallgitlab.md)             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `bitbucket`                                                                                          | [operations.GitProviderGetAllBitbucket](../../models/operations/gitprovidergetallbitbucket.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `github`                                                                                             | [operations.GitProviderGetAllGithub](../../models/operations/gitprovidergetallgithub.md)             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `gitea`                                                                                              | [operations.GitProviderGetAllGitea](../../models/operations/gitprovidergetallgitea.md)               | :heavy_check_mark:                                                                                   | N/A                                                                                                  |