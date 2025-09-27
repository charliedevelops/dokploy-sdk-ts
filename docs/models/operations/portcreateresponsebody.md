# PortCreateResponseBody

Successful response

## Example Usage

```typescript
import { PortCreateResponseBody } from "dokploy-sdk/models/operations";

let value: PortCreateResponseBody = {
  applicationId: "<id>",
  portId: "<id>",
  protocol: "tcp",
  publishMode: "host",
  publishedPort: 3242.98,
  targetPort: 3001.39,
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `portId`                                                                                             | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `protocol`                                                                                           | [operations.PortCreateProtocolResponse](../../models/operations/portcreateprotocolresponse.md)       | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `publishMode`                                                                                        | [operations.PortCreatePublishModeResponse](../../models/operations/portcreatepublishmoderesponse.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `publishedPort`                                                                                      | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `targetPort`                                                                                         | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |