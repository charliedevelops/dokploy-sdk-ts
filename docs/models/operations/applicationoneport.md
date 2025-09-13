# ApplicationOnePort

## Example Usage

```typescript
import { ApplicationOnePort } from "dokploy-sdk/models/operations";

let value: ApplicationOnePort = {
  portId: "<id>",
  publishedPort: 4694.3,
  publishMode: "ingress",
  targetPort: 7137.15,
  protocol: "tcp",
  applicationId: "<id>",
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `portId`                                                                                     | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `publishedPort`                                                                              | *number*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `publishMode`                                                                                | [operations.ApplicationOnePublishMode](../../models/operations/applicationonepublishmode.md) | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `targetPort`                                                                                 | *number*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `protocol`                                                                                   | [operations.ApplicationOneProtocol](../../models/operations/applicationoneprotocol.md)       | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `applicationId`                                                                              | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |