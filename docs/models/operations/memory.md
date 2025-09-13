# Memory

## Example Usage

```typescript
import { Memory } from "dokploy-sdk/models/operations";

let value: Memory = {
  time: "<value>",
  value: {
    total: "<value>",
    used: "<value>",
  },
};
```

## Fields

| Field                                                            | Type                                                             | Required                                                         | Description                                                      |
| ---------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- |
| `time`                                                           | *string*                                                         | :heavy_check_mark:                                               | N/A                                                              |
| `value`                                                          | [operations.MemoryValue](../../models/operations/memoryvalue.md) | :heavy_check_mark:                                               | N/A                                                              |