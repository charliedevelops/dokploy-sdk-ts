# ApplicationReadAppMonitoringResponseBody

Successful response

## Example Usage

```typescript
import { ApplicationReadAppMonitoringResponseBody } from "dokploy-sdk/models/operations";

let value: ApplicationReadAppMonitoringResponseBody = {
  cpu: [
    {
      value: "<value>",
      time: "<value>",
    },
  ],
  memory: [],
  disk: [],
  network: [
    {
      value: {
        inputMb: "<value>",
        outputMb: "<value>",
      },
      time: "<value>",
    },
  ],
  block: [
    {
      value: {
        readMb: "<value>",
        writeMb: "<value>",
      },
      time: "<value>",
    },
  ],
};
```

## Fields

| Field                                                      | Type                                                       | Required                                                   | Description                                                |
| ---------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------------- |
| `cpu`                                                      | [operations.Cpu](../../models/operations/cpu.md)[]         | :heavy_check_mark:                                         | N/A                                                        |
| `memory`                                                   | [operations.Memory](../../models/operations/memory.md)[]   | :heavy_check_mark:                                         | N/A                                                        |
| `disk`                                                     | [operations.Disk](../../models/operations/disk.md)[]       | :heavy_check_mark:                                         | N/A                                                        |
| `network`                                                  | [operations.Network](../../models/operations/network.md)[] | :heavy_check_mark:                                         | N/A                                                        |
| `block`                                                    | [operations.Block](../../models/operations/block.md)[]     | :heavy_check_mark:                                         | N/A                                                        |