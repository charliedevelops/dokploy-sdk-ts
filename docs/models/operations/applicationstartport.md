# ApplicationStartPort

## Example Usage

```typescript
import { ApplicationStartPort } from "dokploy-sdk/models/operations";

let value: ApplicationStartPort = {
  portId: "<id>",
  publishedPort: 4185.05,
  publishMode: "host",
  targetPort: 2651.69,
  protocol: "udp",
  applicationId: "<id>",
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `portId`                                                                                         | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `publishedPort`                                                                                  | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `publishMode`                                                                                    | [operations.ApplicationStartPublishMode](../../models/operations/applicationstartpublishmode.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `targetPort`                                                                                     | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `protocol`                                                                                       | [operations.ApplicationStartProtocol](../../models/operations/applicationstartprotocol.md)       | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |