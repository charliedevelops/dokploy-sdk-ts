# MountsCreateRequest

## Example Usage

```typescript
import { MountsCreateRequest } from "dokploy-sdk/models/operations";

let value: MountsCreateRequest = {
  mountPath: "<value>",
  serviceId: "<id>",
  type: "volume",
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `content`                                                                                | *string*                                                                                 | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `filePath`                                                                               | *string*                                                                                 | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `hostPath`                                                                               | *string*                                                                                 | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `mountPath`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `serviceId`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `serviceType`                                                                            | [operations.MountsCreateServiceType](../../models/operations/mountscreateservicetype.md) | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `type`                                                                                   | [operations.MountsCreateType](../../models/operations/mountscreatetype.md)               | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `volumeName`                                                                             | *string*                                                                                 | :heavy_minus_sign:                                                                       | N/A                                                                                      |