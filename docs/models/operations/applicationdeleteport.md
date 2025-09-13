# ApplicationDeletePort

## Example Usage

```typescript
import { ApplicationDeletePort } from "dokploy-sdk/models/operations";

let value: ApplicationDeletePort = {
  portId: "<id>",
  publishedPort: 9909.06,
  publishMode: "ingress",
  targetPort: 9262.16,
  protocol: "udp",
  applicationId: "<id>",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `portId`                                                                                           | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `publishedPort`                                                                                    | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `publishMode`                                                                                      | [operations.ApplicationDeletePublishMode](../../models/operations/applicationdeletepublishmode.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `targetPort`                                                                                       | *number*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `protocol`                                                                                         | [operations.ApplicationDeleteProtocol](../../models/operations/applicationdeleteprotocol.md)       | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |