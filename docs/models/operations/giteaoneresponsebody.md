# GiteaOneResponseBody

Successful response

## Example Usage

```typescript
import { GiteaOneResponseBody } from "dokploy-sdk/models/operations";

let value: GiteaOneResponseBody = {
  giteaId: "<id>",
  giteaUrl: "https://swift-insolence.com/",
  redirectUri: null,
  clientId: "<id>",
  clientSecret: "<value>",
  gitProviderId: "<id>",
  accessToken: "<value>",
  refreshToken: "<value>",
  expiresAt: 5217.79,
  scopes: "<value>",
  lastAuthenticatedAt: 2570.92,
  gitProvider: {
    gitProviderId: "<id>",
    name: "<value>",
    providerType: "github",
    createdAt: "1722420855653",
    organizationId: "<id>",
    userId: "<id>",
  },
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `giteaId`                                                                        | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `giteaUrl`                                                                       | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `redirectUri`                                                                    | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `clientId`                                                                       | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `clientSecret`                                                                   | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `gitProviderId`                                                                  | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `accessToken`                                                                    | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `refreshToken`                                                                   | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `expiresAt`                                                                      | *number*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `scopes`                                                                         | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `lastAuthenticatedAt`                                                            | *number*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `gitProvider`                                                                    | [operations.GiteaOneGitProvider](../../models/operations/giteaonegitprovider.md) | :heavy_check_mark:                                                               | N/A                                                                              |