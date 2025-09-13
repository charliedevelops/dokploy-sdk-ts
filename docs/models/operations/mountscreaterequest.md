# MountsCreateRequest

## Example Usage

```typescript
import { MountsCreateRequest } from "dokploy-sdk/models/operations";

let value: MountsCreateRequest = {
  type: "volume",
  mountPath: "<value>",
  serviceId: "<id>",
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `type`                                                                                   | [operations.MountsCreateType](../../models/operations/mountscreatetype.md)               | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `hostPath`                                                                               | *string*                                                                                 | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `volumeName`                                                                             | *string*                                                                                 | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `content`                                                                                | *string*                                                                                 | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `mountPath`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `serviceType`                                                                            | [operations.MountsCreateServiceType](../../models/operations/mountscreateservicetype.md) | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `filePath`                                                                               | *string*                                                                                 | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `serviceId`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |