# ApplicationDeleteGitea

## Example Usage

```typescript
import { ApplicationDeleteGitea } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteGitea = {
  giteaId: "<id>",
  giteaUrl: "https://caring-colon.com/",
  redirectUri: null,
  clientId: "<id>",
  clientSecret: "<value>",
  gitProviderId: "<id>",
  accessToken: "<value>",
  refreshToken: "<value>",
  expiresAt: 3648.06,
  scopes: "<value>",
  lastAuthenticatedAt: 8255.7,
};
```

## Fields

| Field                 | Type                  | Required              | Description           |
| --------------------- | --------------------- | --------------------- | --------------------- |
| `giteaId`             | *string*              | :heavy_check_mark:    | N/A                   |
| `giteaUrl`            | *string*              | :heavy_check_mark:    | N/A                   |
| `redirectUri`         | *string*              | :heavy_check_mark:    | N/A                   |
| `clientId`            | *string*              | :heavy_check_mark:    | N/A                   |
| `clientSecret`        | *string*              | :heavy_check_mark:    | N/A                   |
| `gitProviderId`       | *string*              | :heavy_check_mark:    | N/A                   |
| `accessToken`         | *string*              | :heavy_check_mark:    | N/A                   |
| `refreshToken`        | *string*              | :heavy_check_mark:    | N/A                   |
| `expiresAt`           | *number*              | :heavy_check_mark:    | N/A                   |
| `scopes`              | *string*              | :heavy_check_mark:    | N/A                   |
| `lastAuthenticatedAt` | *number*              | :heavy_check_mark:    | N/A                   |