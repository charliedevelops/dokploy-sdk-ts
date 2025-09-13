# ServerSetupMonitoringRequest

## Example Usage

```typescript
import { ServerSetupMonitoringRequest } from "dokploy-sdk/models/operations";

let value: ServerSetupMonitoringRequest = {
  serverId: "<id>",
  metricsConfig: {
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
  },
};
```

## Fields

| Field                                                                                                          | Type                                                                                                           | Required                                                                                                       | Description                                                                                                    |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| `serverId`                                                                                                     | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `metricsConfig`                                                                                                | [operations.ServerSetupMonitoringMetricsConfig](../../models/operations/serversetupmonitoringmetricsconfig.md) | :heavy_check_mark:                                                                                             | N/A                                                                                                            |