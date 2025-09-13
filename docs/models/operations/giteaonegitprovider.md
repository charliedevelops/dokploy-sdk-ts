# GiteaOneGitProvider

## Example Usage

```typescript
import { GiteaOneGitProvider } from "dokploy-sdk/models/operations";

let value: GiteaOneGitProvider = {
  createdAt: "1717207653859",
  gitProviderId: "<id>",
  name: "<value>",
  organizationId: "<id>",
  providerType: "bitbucket",
  userId: "<id>",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `gitProviderId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `name`                                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `organizationId`                                                                   | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `providerType`                                                                     | [operations.GiteaOneProviderType](../../models/operations/giteaoneprovidertype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `userId`                                                                           | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |