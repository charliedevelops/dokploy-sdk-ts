# AdminSetupMonitoringMetricsConfig

## Example Usage

```typescript
import { AdminSetupMonitoringMetricsConfig } from "dokploy-sdk/models/operations";

let value: AdminSetupMonitoringMetricsConfig = {
  server: {
    refreshRate: 7287.37,
    port: 475.39,
    token: "<value>",
    urlCallback: "https://profuse-pantyhose.name",
    retentionDays: 3313.33,
    cronJob: "<value>",
    thresholds: {
      cpu: 3248.61,
      memory: 4250.23,
    },
  },
  containers: {
    refreshRate: 4903.01,
    services: {},
  },
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `server`                                                                                               | [operations.AdminSetupMonitoringServer](../../models/operations/adminsetupmonitoringserver.md)         | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `containers`                                                                                           | [operations.AdminSetupMonitoringContainers](../../models/operations/adminsetupmonitoringcontainers.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |