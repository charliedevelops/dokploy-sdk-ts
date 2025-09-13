# PortUpdateResponseBody

Successful response

## Example Usage

```typescript
import { PortUpdateResponseBody } from "dokploy-sdk/models/operations";

let value: PortUpdateResponseBody = {
  applicationId: "<id>",
  portId: "<id>",
  protocol: "udp",
  publishMode: "ingress",
  publishedPort: 1095.55,
  targetPort: 3732.15,
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `portId`                                                                                             | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `protocol`                                                                                           | [operations.PortUpdateProtocolResponse](../../models/operations/portupdateprotocolresponse.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `publishMode`                                                                                        | [operations.PortUpdatePublishModeResponse](../../models/operations/portupdatepublishmoderesponse.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `publishedPort`                                                                                      | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `targetPort`                                                                                         | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |