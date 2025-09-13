# GithubOneGitProvider

## Example Usage

```typescript
import { GithubOneGitProvider } from "dokploy-sdk/models/operations";

let value: GithubOneGitProvider = {
  gitProviderId: "<id>",
  name: "<value>",
  providerType: "bitbucket",
  createdAt: "1708123182409",
  organizationId: "<id>",
  userId: "<id>",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `gitProviderId`                                                                      | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `providerType`                                                                       | [operations.GithubOneProviderType](../../models/operations/githuboneprovidertype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `organizationId`                                                                     | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `userId`                                                                             | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |