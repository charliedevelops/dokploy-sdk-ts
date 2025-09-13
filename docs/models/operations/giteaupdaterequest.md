# GiteaUpdateRequest

## Example Usage

```typescript
import { GiteaUpdateRequest } from "dokploy-sdk/models/operations";

let value: GiteaUpdateRequest = {
  gitProviderId: "<id>",
  giteaId: "<id>",
  giteaUrl: "https://probable-simple.info/",
  name: "<value>",
};
```

## Fields

| Field                 | Type                  | Required              | Description           |
| --------------------- | --------------------- | --------------------- | --------------------- |
| `accessToken`         | *string*              | :heavy_minus_sign:    | N/A                   |
| `clientId`            | *string*              | :heavy_minus_sign:    | N/A                   |
| `clientSecret`        | *string*              | :heavy_minus_sign:    | N/A                   |
| `expiresAt`           | *number*              | :heavy_minus_sign:    | N/A                   |
| `gitProviderId`       | *string*              | :heavy_check_mark:    | N/A                   |
| `giteaId`             | *string*              | :heavy_check_mark:    | N/A                   |
| `giteaUrl`            | *string*              | :heavy_check_mark:    | N/A                   |
| `giteaUsername`       | *string*              | :heavy_minus_sign:    | N/A                   |
| `lastAuthenticatedAt` | *number*              | :heavy_minus_sign:    | N/A                   |
| `name`                | *string*              | :heavy_check_mark:    | N/A                   |
| `organizationName`    | *string*              | :heavy_minus_sign:    | N/A                   |
| `redirectUri`         | *string*              | :heavy_minus_sign:    | N/A                   |
| `refreshToken`        | *string*              | :heavy_minus_sign:    | N/A                   |
| `scopes`              | *string*              | :heavy_minus_sign:    | N/A                   |