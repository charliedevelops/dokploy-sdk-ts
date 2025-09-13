# ServerSetupMonitoringMetricsConfig

## Example Usage

```typescript
import { ServerSetupMonitoringMetricsConfig } from "dokploy-sdk/models/operations";

let value: ServerSetupMonitoringMetricsConfig = {
  server: {
    refreshRate: 41.38,
    port: 1267.7,
    token: "<value>",
    urlCallback: "https://unique-monocle.name",
    retentionDays: 858.77,
    cronJob: "<value>",
    thresholds: {
      cpu: 4056.95,
      memory: 3236.65,
    },
  },
  containers: {
    refreshRate: 367.81,
    services: {},
  },
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `server`                                                                                                 | [operations.ServerSetupMonitoringServer](../../models/operations/serversetupmonitoringserver.md)         | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `containers`                                                                                             | [operations.ServerSetupMonitoringContainers](../../models/operations/serversetupmonitoringcontainers.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |