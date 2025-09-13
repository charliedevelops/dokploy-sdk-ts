# Memory

## Example Usage

```typescript
import { Memory } from "dokploy-sdk/models/operations";

let value: Memory = {
  value: {
    used: "<value>",
    total: "<value>",
  },
  time: "<value>",
};
```

## Fields

| Field                                                            | Type                                                             | Required                                                         | Description                                                      |
| ---------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- |
| `value`                                                          | [operations.MemoryValue](../../models/operations/memoryvalue.md) | :heavy_check_mark:                                               | N/A                                                              |
| `time`                                                           | *string*                                                         | :heavy_check_mark:                                               | N/A                                                              |