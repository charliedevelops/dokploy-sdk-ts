# ApplicationStopPort

## Example Usage

```typescript
import { ApplicationStopPort } from "dokploy-sdk/models/operations";

let value: ApplicationStopPort = {
  applicationId: "<id>",
  portId: "<id>",
  protocol: "tcp",
  publishMode: "ingress",
  publishedPort: 2301.95,
  targetPort: 9679.9,
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `portId`                                                                                       | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `protocol`                                                                                     | [operations.ApplicationStopProtocol](../../models/operations/applicationstopprotocol.md)       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `publishMode`                                                                                  | [operations.ApplicationStopPublishMode](../../models/operations/applicationstoppublishmode.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `publishedPort`                                                                                | *number*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `targetPort`                                                                                   | *number*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |