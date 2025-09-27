# BitbucketOneGitProvider

## Example Usage

```typescript
import { BitbucketOneGitProvider } from "dokploy-sdk/models/operations";

let value: BitbucketOneGitProvider = {
  createdAt: "1728269203395",
  gitProviderId: "<id>",
  name: "<value>",
  organizationId: "<id>",
  providerType: "github",
  userId: "<id>",
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `createdAt`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `gitProviderId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `organizationId`                                                                           | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `providerType`                                                                             | [operations.BitbucketOneProviderType](../../models/operations/bitbucketoneprovidertype.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `userId`                                                                                   | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |