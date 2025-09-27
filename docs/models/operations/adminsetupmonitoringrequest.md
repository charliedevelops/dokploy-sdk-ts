# AdminSetupMonitoringRequest

## Example Usage

```typescript
import { AdminSetupMonitoringRequest } from "dokploy-sdk/models/operations";

let value: AdminSetupMonitoringRequest = {
  metricsConfig: {
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
  },
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `metricsConfig`                                                                                              | [operations.AdminSetupMonitoringMetricsConfig](../../models/operations/adminsetupmonitoringmetricsconfig.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |