# ApplicationStartGitea

## Example Usage

```typescript
import { ApplicationStartGitea } from "dokploy-sdk/models/operations";

let value: ApplicationStartGitea = {
  giteaId: "<id>",
  giteaUrl: "https://acclaimed-derby.org",
  redirectUri: "https://possible-sushi.com/",
  clientId: "<id>",
  clientSecret: "<value>",
  gitProviderId: "<id>",
  accessToken: "<value>",
  refreshToken: "<value>",
  expiresAt: 4635.61,
  scopes: "<value>",
  lastAuthenticatedAt: 7182.32,
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