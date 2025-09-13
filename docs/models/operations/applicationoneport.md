# ApplicationOnePort

## Example Usage

```typescript
import { ApplicationOnePort } from "dokploy-sdk/models/operations";

let value: ApplicationOnePort = {
  applicationId: "<id>",
  portId: "<id>",
  protocol: "tcp",
  publishMode: "ingress",
  publishedPort: 7137.15,
  targetPort: 617.97,
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `applicationId`                                                                              | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `portId`                                                                                     | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `protocol`                                                                                   | [operations.ApplicationOneProtocol](../../models/operations/applicationoneprotocol.md)       | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `publishMode`                                                                                | [operations.ApplicationOnePublishMode](../../models/operations/applicationonepublishmode.md) | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `publishedPort`                                                                              | *number*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `targetPort`                                                                                 | *number*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |