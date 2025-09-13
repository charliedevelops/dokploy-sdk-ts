# AdminSetupMonitoringServer

## Example Usage

```typescript
import { AdminSetupMonitoringServer } from "dokploy-sdk/models/operations";

let value: AdminSetupMonitoringServer = {
  refreshRate: 1296.48,
  port: 4132.13,
  token: "<value>",
  urlCallback: "https://french-colon.biz/",
  retentionDays: 3868.29,
  cronJob: "<value>",
  thresholds: {
    cpu: 3248.61,
    memory: 4250.23,
  },
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `refreshRate`                                                                                          | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `port`                                                                                                 | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `token`                                                                                                | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `urlCallback`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `retentionDays`                                                                                        | *number*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `cronJob`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `thresholds`                                                                                           | [operations.AdminSetupMonitoringThresholds](../../models/operations/adminsetupmonitoringthresholds.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |