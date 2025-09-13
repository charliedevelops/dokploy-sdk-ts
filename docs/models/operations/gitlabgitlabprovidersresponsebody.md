# GitlabGitlabProvidersResponseBody

## Example Usage

```typescript
import { GitlabGitlabProvidersResponseBody } from "dokploy-sdk/models/operations";

let value: GitlabGitlabProvidersResponseBody = {
  gitlabId: "<id>",
  gitProvider: {
    gitProviderId: "<id>",
    name: "<value>",
    providerType: "github",
    createdAt: "1732934313716",
    organizationId: "<id>",
    userId: "<id>",
  },
  gitlabUrl: "https://terrible-sushi.org",
};
```

## Fields

| Field                                                                                                      | Type                                                                                                       | Required                                                                                                   | Description                                                                                                |
| ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `gitlabId`                                                                                                 | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `gitProvider`                                                                                              | [operations.GitlabGitlabProvidersGitProvider](../../models/operations/gitlabgitlabprovidersgitprovider.md) | :heavy_check_mark:                                                                                         | N/A                                                                                                        |
| `gitlabUrl`                                                                                                | *string*                                                                                                   | :heavy_check_mark:                                                                                         | N/A                                                                                                        |