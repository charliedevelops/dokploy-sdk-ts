# ApplicationStartPort

## Example Usage

```typescript
import { ApplicationStartPort } from "dokploy-sdk/models/operations";

let value: ApplicationStartPort = {
  applicationId: "<id>",
  portId: "<id>",
  protocol: "tcp",
  publishMode: "host",
  publishedPort: 2651.69,
  targetPort: 7981.39,
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `applicationId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `portId`                                                                                         | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `protocol`                                                                                       | [operations.ApplicationStartProtocol](../../models/operations/applicationstartprotocol.md)       | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `publishMode`                                                                                    | [operations.ApplicationStartPublishMode](../../models/operations/applicationstartpublishmode.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `publishedPort`                                                                                  | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `targetPort`                                                                                     | *number*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |