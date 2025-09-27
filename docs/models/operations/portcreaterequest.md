# PortCreateRequest

## Example Usage

```typescript
import { PortCreateRequest } from "dokploy-sdk/models/operations";

let value: PortCreateRequest = {
  applicationId: "<id>",
  publishedPort: 1244.1,
  targetPort: 6872.55,
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `protocol`                                                                                         | [operations.PortCreateProtocolRequest](../../models/operations/portcreateprotocolrequest.md)       | :heavy_minus_sign:                                                                                 | N/A                                                                                                |
| `publishMode`                                                                                      | [operations.PortCreatePublishModeRequest](../../models/operations/portcreatepublishmoderequest.md) | :heavy_minus_sign:                                                                                 | N/A                                                                                                |
| `publishedPort`                                                                                    | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `targetPort`                                                                                       | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |