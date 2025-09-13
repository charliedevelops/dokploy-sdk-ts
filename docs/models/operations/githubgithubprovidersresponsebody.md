# GithubGithubProvidersResponseBody

## Example Usage

```typescript
import { GithubGithubProvidersResponseBody } from "dokploy-sdk/models/operations";

let value: GithubGithubProvidersResponseBody = {
  githubId: "<id>",
  gitProvider: {
    gitProviderId: "<id>",
    name: "<value>",
    providerType: "gitlab",
    createdAt: "1728545338786",
    organizationId: "<id>",
    userId: "<id>",
  },
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `githubId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `gitProvider`                                                                                              | [operations.GithubGithubProvidersGitProvider](../../models/operations/githubgithubprovidersgitprovider.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |