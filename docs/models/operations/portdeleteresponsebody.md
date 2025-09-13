# PortDeleteResponseBody

Successful response

## Example Usage

```typescript
import { PortDeleteResponseBody } from "dokploy-sdk/models/operations";

let value: PortDeleteResponseBody = {
  applicationId: "<id>",
  portId: "<id>",
  protocol: "udp",
  publishMode: "ingress",
  publishedPort: 9274.32,
  targetPort: 7871.89,
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `applicationId`                                                                      | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `portId`                                                                             | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `protocol`                                                                           | [operations.PortDeleteProtocol](../../models/operations/portdeleteprotocol.md)       | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `publishMode`                                                                        | [operations.PortDeletePublishMode](../../models/operations/portdeletepublishmode.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `publishedPort`                                                                      | *number*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `targetPort`                                                                         | *number*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |