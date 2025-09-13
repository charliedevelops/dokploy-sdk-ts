# PortCreateResponseBody

Successful response

## Example Usage

```typescript
import { PortCreateResponseBody } from "dokploy-sdk/models/operations";

let value: PortCreateResponseBody = {
  portId: "<id>",
  publishedPort: 813.61,
  publishMode: "host",
  targetPort: 3242.98,
  protocol: "tcp",
  applicationId: "<id>",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `portId`                                                                                             | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `publishedPort`                                                                                      | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `publishMode`                                                                                        | [operations.PortCreatePublishModeResponse](../../models/operations/portcreatepublishmoderesponse.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `targetPort`                                                                                         | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `protocol`                                                                                           | [operations.PortCreateProtocolResponse](../../models/operations/portcreateprotocolresponse.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |