# ApplicationDeletePort

## Example Usage

```typescript
import { ApplicationDeletePort } from "dokploy-sdk/models/operations";

let value: ApplicationDeletePort = {
  applicationId: "<id>",
  portId: "<id>",
  protocol: "udp",
  publishMode: "ingress",
  publishedPort: 9262.16,
  targetPort: 7733.55,
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `portId`                                                                                           | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `protocol`                                                                                         | [operations.ApplicationDeleteProtocol](../../models/operations/applicationdeleteprotocol.md)       | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `publishMode`                                                                                      | [operations.ApplicationDeletePublishMode](../../models/operations/applicationdeletepublishmode.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `publishedPort`                                                                                    | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `targetPort`                                                                                       | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |