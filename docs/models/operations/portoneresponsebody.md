# PortOneResponseBody

Successful response

## Example Usage

```typescript
import { PortOneResponseBody } from "dokploy-sdk/models/operations";

let value: PortOneResponseBody = {
  applicationId: "<id>",
  portId: "<id>",
  protocol: "tcp",
  publishMode: "ingress",
  publishedPort: 22.99,
  targetPort: 2782.63,
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `applicationId`                                                                | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `portId`                                                                       | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `protocol`                                                                     | [operations.PortOneProtocol](../../models/operations/portoneprotocol.md)       | :heavy_check_mark:                                                             | N/A                                                                            |
| `publishMode`                                                                  | [operations.PortOnePublishMode](../../models/operations/portonepublishmode.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `publishedPort`                                                                | *number*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `targetPort`                                                                   | *number*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |