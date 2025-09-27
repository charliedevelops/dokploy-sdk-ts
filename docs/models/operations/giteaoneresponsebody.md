# GiteaOneResponseBody

Successful response

## Example Usage

```typescript
import { GiteaOneResponseBody } from "dokploy-sdk/models/operations";

let value: GiteaOneResponseBody = {
  accessToken: null,
  clientId: "<id>",
  clientSecret: "<value>",
  expiresAt: 196.36,
  gitProvider: {
    createdAt: "1708082730636",
    gitProviderId: "<id>",
    name: "<value>",
    organizationId: "<id>",
    providerType: "gitlab",
    userId: "<id>",
  },
  gitProviderId: "<id>",
  giteaId: "<id>",
  giteaUrl: "https://infamous-haircut.name",
  lastAuthenticatedAt: 7810.54,
  redirectUri: "https://ornate-perfection.name/",
  refreshToken: null,
  scopes: "<value>",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `accessToken`                                                                    | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `clientId`                                                                       | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `clientSecret`                                                                   | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `expiresAt`                                                                      | *number*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `gitProvider`                                                                    | [operations.GiteaOneGitProvider](../../models/operations/giteaonegitprovider.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `gitProviderId`                                                                  | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `giteaId`                                                                        | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `giteaUrl`                                                                       | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `lastAuthenticatedAt`                                                            | *number*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `redirectUri`                                                                    | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `refreshToken`                                                                   | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `scopes`                                                                         | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |