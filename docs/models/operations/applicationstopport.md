# ApplicationStopPort

## Example Usage

```typescript
import { ApplicationStopPort } from "dokploy-sdk/models/operations";

let value: ApplicationStopPort = {
  portId: "<id>",
  publishedPort: 3486.19,
  publishMode: "ingress",
  targetPort: 2301.95,
  protocol: "udp",
  applicationId: "<id>",
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `portId`                                                                                       | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `publishedPort`                                                                                | *number*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `publishMode`                                                                                  | [operations.ApplicationStopPublishMode](../../models/operations/applicationstoppublishmode.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `targetPort`                                                                                   | *number*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `protocol`                                                                                     | [operations.ApplicationStopProtocol](../../models/operations/applicationstopprotocol.md)       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `applicationId`                                                                                | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |