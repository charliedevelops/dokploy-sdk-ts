# GiteaCreateRequest

## Example Usage

```typescript
import { GiteaCreateRequest } from "dokploy-sdk/models/operations";

let value: GiteaCreateRequest = {
  giteaUrl: "https://fond-dusk.info",
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
| `gitProviderId`       | *string*              | :heavy_minus_sign:    | N/A                   |
| `giteaId`             | *string*              | :heavy_minus_sign:    | N/A                   |
| `giteaUrl`            | *string*              | :heavy_check_mark:    | N/A                   |
| `giteaUsername`       | *string*              | :heavy_minus_sign:    | N/A                   |
| `lastAuthenticatedAt` | *number*              | :heavy_minus_sign:    | N/A                   |
| `name`                | *string*              | :heavy_check_mark:    | N/A                   |
| `organizationName`    | *string*              | :heavy_minus_sign:    | N/A                   |
| `redirectUri`         | *string*              | :heavy_minus_sign:    | N/A                   |
| `refreshToken`        | *string*              | :heavy_minus_sign:    | N/A                   |
| `scopes`              | *string*              | :heavy_minus_sign:    | N/A                   |