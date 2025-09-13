# BitbucketOneGitProvider

## Example Usage

```typescript
import { BitbucketOneGitProvider } from "dokploy-sdk/models/operations";

let value: BitbucketOneGitProvider = {
  gitProviderId: "<id>",
  name: "<value>",
  providerType: "gitea",
  createdAt: "1704214428482",
  organizationId: "<id>",
  userId: "<id>",
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `gitProviderId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `providerType`                                                                             | [operations.BitbucketOneProviderType](../../models/operations/bitbucketoneprovidertype.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `createdAt`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `organizationId`                                                                           | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `userId`                                                                                   | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |