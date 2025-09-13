# PortOneResponseBody

Successful response

## Example Usage

```typescript
import { PortOneResponseBody } from "dokploy-sdk/models/operations";

let value: PortOneResponseBody = {
  portId: "<id>",
  publishedPort: 2075.33,
  publishMode: "ingress",
  targetPort: 22.99,
  protocol: "tcp",
  applicationId: "<id>",
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `portId`                                                                       | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `publishedPort`                                                                | *number*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `publishMode`                                                                  | [operations.PortOnePublishMode](../../models/operations/portonepublishmode.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `targetPort`                                                                   | *number*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `protocol`                                                                     | [operations.PortOneProtocol](../../models/operations/portoneprotocol.md)       | :heavy_check_mark:                                                             | N/A                                                                            |
| `applicationId`                                                                | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |