# ApplicationReadAppMonitoringResponseBody

Successful response

## Example Usage

```typescript
import { ApplicationReadAppMonitoringResponseBody } from "dokploy-sdk/models/operations";

let value: ApplicationReadAppMonitoringResponseBody = {
  block: [
    {
      time: "<value>",
      value: {
        readMb: "<value>",
        writeMb: "<value>",
      },
    },
  ],
  cpu: [],
  disk: [],
  memory: [
    {
      time: "<value>",
      value: {
        total: "<value>",
        used: "<value>",
      },
    },
  ],
  network: [
    {
      time: "<value>",
      value: {
        inputMb: "<value>",
        outputMb: "<value>",
      },
    },
  ],
};
```

## Fields

| Field                                                      | Type                                                       | Required                                                   | Description                                                |
| ---------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------------- |
| `block`                                                    | [operations.Block](../../models/operations/block.md)[]     | :heavy_check_mark:                                         | N/A                                                        |
| `cpu`                                                      | [operations.Cpu](../../models/operations/cpu.md)[]         | :heavy_check_mark:                                         | N/A                                                        |
| `disk`                                                     | [operations.Disk](../../models/operations/disk.md)[]       | :heavy_check_mark:                                         | N/A                                                        |
| `memory`                                                   | [operations.Memory](../../models/operations/memory.md)[]   | :heavy_check_mark:                                         | N/A                                                        |
| `network`                                                  | [operations.Network](../../models/operations/network.md)[] | :heavy_check_mark:                                         | N/A                                                        |