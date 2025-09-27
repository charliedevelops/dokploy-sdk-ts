# AdminSetupMonitoringMetricsConfig

## Example Usage

```typescript
import { AdminSetupMonitoringMetricsConfig } from "dokploy-sdk/models/operations";

let value: AdminSetupMonitoringMetricsConfig = {
  containers: {
    refreshRate: 7287.37,
    services: {},
  },
  server: {
    cronJob: "<value>",
    port: 475.39,
    refreshRate: 8230.4,
    retentionDays: 6413.78,
    thresholds: {
      cpu: 2952.89,
      memory: 1676.7,
    },
    token: "<value>",
    urlCallback: "https://proper-finding.info",
  },
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `containers`                                                                                           | [operations.AdminSetupMonitoringContainers](../../models/operations/adminsetupmonitoringcontainers.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `server`                                                                                               | [operations.AdminSetupMonitoringServer](../../models/operations/adminsetupmonitoringserver.md)         | :heavy_check_mark:                                                                                     | N/A                                                                                                    |