# GiteaUpdateRequest

## Example Usage

```typescript
import { GiteaUpdateRequest } from "dokploy-sdk/models/operations";

let value: GiteaUpdateRequest = {
  giteaId: "<id>",
  giteaUrl: "https://probable-simple.info/",
  gitProviderId: "<id>",
  name: "<value>",
};
```

## Fields

| Field                 | Type                  | Required              | Description           |
| --------------------- | --------------------- | --------------------- | --------------------- |
| `giteaId`             | *string*              | :heavy_check_mark:    | N/A                   |
| `giteaUrl`            | *string*              | :heavy_check_mark:    | N/A                   |
| `redirectUri`         | *string*              | :heavy_minus_sign:    | N/A                   |
| `clientId`            | *string*              | :heavy_minus_sign:    | N/A                   |
| `clientSecret`        | *string*              | :heavy_minus_sign:    | N/A                   |
| `gitProviderId`       | *string*              | :heavy_check_mark:    | N/A                   |
| `accessToken`         | *string*              | :heavy_minus_sign:    | N/A                   |
| `refreshToken`        | *string*              | :heavy_minus_sign:    | N/A                   |
| `expiresAt`           | *number*              | :heavy_minus_sign:    | N/A                   |
| `scopes`              | *string*              | :heavy_minus_sign:    | N/A                   |
| `lastAuthenticatedAt` | *number*              | :heavy_minus_sign:    | N/A                   |
| `name`                | *string*              | :heavy_check_mark:    | N/A                   |
| `giteaUsername`       | *string*              | :heavy_minus_sign:    | N/A                   |
| `organizationName`    | *string*              | :heavy_minus_sign:    | N/A                   |