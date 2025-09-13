# ServerSetupMonitoringServer

## Example Usage

```typescript
import { ServerSetupMonitoringServer } from "dokploy-sdk/models/operations";

let value: ServerSetupMonitoringServer = {
  cronJob: "<value>",
  port: 6011.09,
  refreshRate: 3069.77,
  retentionDays: 3180.42,
  thresholds: {
    cpu: 1394.41,
    memory: 5211.2,
  },
  token: "<value>",
  urlCallback: "https://delicious-haircut.biz",
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `cronJob`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `port`                                                                                                   | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `refreshRate`                                                                                            | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `retentionDays`                                                                                          | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `thresholds`                                                                                             | [operations.ServerSetupMonitoringThresholds](../../models/operations/serversetupmonitoringthresholds.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `token`                                                                                                  | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `urlCallback`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |