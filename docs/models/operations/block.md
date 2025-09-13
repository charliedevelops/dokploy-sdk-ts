# Block

## Example Usage

```typescript
import { Block } from "dokploy-sdk/models/operations";

let value: Block = {
  value: {
    readMb: "<value>",
    writeMb: "<value>",
  },
  time: "<value>",
};
```

## Fields

| Field                                                          | Type                                                           | Required                                                       | Description                                                    |
| -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- |
| `value`                                                        | [operations.BlockValue](../../models/operations/blockvalue.md) | :heavy_check_mark:                                             | N/A                                                            |
| `time`                                                         | *string*                                                       | :heavy_check_mark:                                             | N/A                                                            |