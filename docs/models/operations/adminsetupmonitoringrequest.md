# AdminSetupMonitoringRequest

## Example Usage

```typescript
import { AdminSetupMonitoringRequest } from "dokploy-sdk/models/operations";

let value: AdminSetupMonitoringRequest = {
  metricsConfig: {
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
  },
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `metricsConfig`                                                                                              | [operations.AdminSetupMonitoringMetricsConfig](../../models/operations/adminsetupmonitoringmetricsconfig.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |