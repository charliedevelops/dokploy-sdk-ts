# PortUpdateResponseBody

Successful response

## Example Usage

```typescript
import { PortUpdateResponseBody } from "dokploy-sdk/models/operations";

let value: PortUpdateResponseBody = {
  portId: "<id>",
  publishedPort: 9527.54,
  publishMode: "ingress",
  targetPort: 1095.55,
  protocol: "tcp",
  applicationId: "<id>",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `portId`                                                                                             | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `publishedPort`                                                                                      | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `publishMode`                                                                                        | [operations.PortUpdatePublishModeResponse](../../models/operations/portupdatepublishmoderesponse.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `targetPort`                                                                                         | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `protocol`                                                                                           | [operations.PortUpdateProtocolResponse](../../models/operations/portupdateprotocolresponse.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |