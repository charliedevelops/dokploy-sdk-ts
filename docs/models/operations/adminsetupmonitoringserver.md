# AdminSetupMonitoringServer

## Example Usage

```typescript
import { AdminSetupMonitoringServer } from "dokploy-sdk/models/operations";

let value: AdminSetupMonitoringServer = {
  cronJob: "<value>",
  port: 1296.48,
  refreshRate: 4132.13,
  retentionDays: 2520.06,
  thresholds: {
    cpu: 2952.89,
    memory: 1676.7,
  },
  token: "<value>",
  urlCallback: "https://ignorant-fen.info/",
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `cronJob`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `port`                                                                                                 | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `refreshRate`                                                                                          | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `retentionDays`                                                                                        | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `thresholds`                                                                                           | [operations.AdminSetupMonitoringThresholds](../../models/operations/adminsetupmonitoringthresholds.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `token`                                                                                                | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `urlCallback`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |