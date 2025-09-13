# GiteaOneGitProvider

## Example Usage

```typescript
import { GiteaOneGitProvider } from "dokploy-sdk/models/operations";

let value: GiteaOneGitProvider = {
  gitProviderId: "<id>",
  name: "<value>",
  providerType: "gitlab",
  createdAt: "1725032285450",
  organizationId: "<id>",
  userId: "<id>",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `gitProviderId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `name`                                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `providerType`                                                                     | [operations.GiteaOneProviderType](../../models/operations/giteaoneprovidertype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `organizationId`                                                                   | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `userId`                                                                           | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |