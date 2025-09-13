# GitlabOneGitProvider

## Example Usage

```typescript
import { GitlabOneGitProvider } from "dokploy-sdk/models/operations";

let value: GitlabOneGitProvider = {
  createdAt: "1710331647774",
  gitProviderId: "<id>",
  name: "<value>",
  organizationId: "<id>",
  providerType: "gitea",
  userId: "<id>",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `gitProviderId`                                                                      | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `organizationId`                                                                     | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `providerType`                                                                       | [operations.GitlabOneProviderType](../../models/operations/gitlaboneprovidertype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `userId`                                                                             | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |