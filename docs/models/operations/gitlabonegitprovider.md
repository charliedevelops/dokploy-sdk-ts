# GitlabOneGitProvider

## Example Usage

```typescript
import { GitlabOneGitProvider } from "dokploy-sdk/models/operations";

let value: GitlabOneGitProvider = {
  gitProviderId: "<id>",
  name: "<value>",
  providerType: "github",
  createdAt: "1735113710864",
  organizationId: "<id>",
  userId: "<id>",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `gitProviderId`                                                                      | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `providerType`                                                                       | [operations.GitlabOneProviderType](../../models/operations/gitlaboneprovidertype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `organizationId`                                                                     | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `userId`                                                                             | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |