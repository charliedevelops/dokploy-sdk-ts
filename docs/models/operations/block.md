# Block

## Example Usage

```typescript
import { Block } from "dokploy-sdk/models/operations";

let value: Block = {
  time: "<value>",
  value: {
    readMb: "<value>",
    writeMb: "<value>",
  },
};
```

## Fields

| Field                                                          | Type                                                           | Required                                                       | Description                                                    |
| -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- |
| `time`                                                         | *string*                                                       | :heavy_check_mark:                                             | N/A                                                            |
| `value`                                                        | [operations.BlockValue](../../models/operations/blockvalue.md) | :heavy_check_mark:                                             | N/A                                                            |