# PortDeleteResponseBody

Successful response

## Example Usage

```typescript
import { PortDeleteResponseBody } from "dokploy-sdk/models/operations";

let value: PortDeleteResponseBody = {
  portId: "<id>",
  publishedPort: 6036.67,
  publishMode: "ingress",
  targetPort: 9274.32,
  protocol: "udp",
  applicationId: "<id>",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `portId`                                                                             | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `publishedPort`                                                                      | *number*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `publishMode`                                                                        | [operations.PortDeletePublishMode](../../models/operations/portdeletepublishmode.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `targetPort`                                                                         | *number*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `protocol`                                                                           | [operations.PortDeleteProtocol](../../models/operations/portdeleteprotocol.md)       | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `applicationId`                                                                      | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |