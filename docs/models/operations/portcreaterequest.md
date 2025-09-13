# PortCreateRequest

## Example Usage

```typescript
import { PortCreateRequest } from "dokploy-sdk/models/operations";

let value: PortCreateRequest = {
  publishedPort: 1244.1,
  targetPort: 6872.55,
  applicationId: "<id>",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `publishedPort`                                                                                    | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `publishMode`                                                                                      | [operations.PortCreatePublishModeRequest](../../models/operations/portcreatepublishmoderequest.md) | :heavy_minus_sign:                                                                                 | N/A                                                                                                |
| `targetPort`                                                                                       | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `protocol`                                                                                         | [operations.PortCreateProtocolRequest](../../models/operations/portcreateprotocolrequest.md)       | :heavy_minus_sign:                                                                                 | N/A                                                                                                |
| `applicationId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |