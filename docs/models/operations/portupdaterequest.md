# PortUpdateRequest

## Example Usage

```typescript
import { PortUpdateRequest } from "dokploy-sdk/models/operations";

let value: PortUpdateRequest = {
  portId: "<id>",
  publishedPort: 8649.89,
  targetPort: 6568.3,
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `portId`                                                                                           | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `protocol`                                                                                         | [operations.PortUpdateProtocolRequest](../../models/operations/portupdateprotocolrequest.md)       | :heavy_minus_sign:                                                                                 | N/A                                                                                                |
| `publishMode`                                                                                      | [operations.PortUpdatePublishModeRequest](../../models/operations/portupdatepublishmoderequest.md) | :heavy_minus_sign:                                                                                 | N/A                                                                                                |
| `publishedPort`                                                                                    | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `targetPort`                                                                                       | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |