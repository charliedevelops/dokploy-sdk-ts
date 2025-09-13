# ServerSetupMonitoringServer

## Example Usage

```typescript
import { ServerSetupMonitoringServer } from "dokploy-sdk/models/operations";

let value: ServerSetupMonitoringServer = {
  refreshRate: 6011.09,
  port: 3069.77,
  token: "<value>",
  urlCallback: "https://cool-lender.org/",
  retentionDays: 1807.95,
  cronJob: "<value>",
  thresholds: {
    cpu: 4056.95,
    memory: 3236.65,
  },
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `refreshRate`                                                                                            | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `port`                                                                                                   | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `token`                                                                                                  | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `urlCallback`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `retentionDays`                                                                                          | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `cronJob`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `thresholds`                                                                                             | [operations.ServerSetupMonitoringThresholds](../../models/operations/serversetupmonitoringthresholds.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |