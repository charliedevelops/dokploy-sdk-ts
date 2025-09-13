# UserCreateApiKeyRequest

## Example Usage

```typescript
import { UserCreateApiKeyRequest } from "dokploy-sdk/models/operations";

let value: UserCreateApiKeyRequest = {
  name: "<value>",
  metadata: {
    organizationId: "<id>",
  },
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `prefix`                                                                                   | *string*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `expiresIn`                                                                                | *number*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `metadata`                                                                                 | [operations.UserCreateApiKeyMetadata](../../models/operations/usercreateapikeymetadata.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `rateLimitEnabled`                                                                         | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `rateLimitTimeWindow`                                                                      | *number*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `rateLimitMax`                                                                             | *number*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `remaining`                                                                                | *number*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `refillAmount`                                                                             | *number*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `refillInterval`                                                                           | *number*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |