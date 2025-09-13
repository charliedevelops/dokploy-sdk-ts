# Network

## Example Usage

```typescript
import { Network } from "dokploy-sdk/models/operations";

let value: Network = {
  time: "<value>",
  value: {
    inputMb: "<value>",
    outputMb: "<value>",
  },
};
```

## Fields

| Field                                                              | Type                                                               | Required                                                           | Description                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| `time`                                                             | *string*                                                           | :heavy_check_mark:                                                 | N/A                                                                |
| `value`                                                            | [operations.NetworkValue](../../models/operations/networkvalue.md) | :heavy_check_mark:                                                 | N/A                                                                |