# GithubGithubProvidersResponseBody

## Example Usage

```typescript
import { GithubGithubProvidersResponseBody } from "dokploy-sdk/models/operations";

let value: GithubGithubProvidersResponseBody = {
  gitProvider: {
    createdAt: "1715267301320",
    gitProviderId: "<id>",
    name: "<value>",
    organizationId: "<id>",
    providerType: "gitea",
    userId: "<id>",
  },
  githubId: "<id>",
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `gitProvider`                                                                                              | [operations.GithubGithubProvidersGitProvider](../../models/operations/githubgithubprovidersgitprovider.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `githubId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |