# GithubOneGitProvider

## Example Usage

```typescript
import { GithubOneGitProvider } from "dokploy-sdk/models/operations";

let value: GithubOneGitProvider = {
  createdAt: "1725878748765",
  gitProviderId: "<id>",
  name: "<value>",
  organizationId: "<id>",
  providerType: "github",
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
| `providerType`                                                                       | [operations.GithubOneProviderType](../../models/operations/githuboneprovidertype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `userId`                                                                             | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |