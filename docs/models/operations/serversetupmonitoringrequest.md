# ServerSetupMonitoringRequest

## Example Usage

```typescript
import { ServerSetupMonitoringRequest } from "dokploy-sdk/models/operations";

let value: ServerSetupMonitoringRequest = {
  metricsConfig: {
    containers: {
      refreshRate: 41.38,
      services: {},
    },
    server: {
      cronJob: "<value>",
      port: 1267.7,
      refreshRate: 6432.34,
      retentionDays: 8913.64,
      thresholds: {
        cpu: 1394.41,
        memory: 5211.2,
      },
      token: "<value>",
      urlCallback: "https://plain-blowgun.com",
    },
  },
  serverId: "<id>",
};
```

## Fields

| Field                                                                                                          | Type                                                                                                           | Required                                                                                                       | Description                                                                                                    |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| `metricsConfig`                                                                                                | [operations.ServerSetupMonitoringMetricsConfig](../../models/operations/serversetupmonitoringmetricsconfig.md) | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `serverId`                                                                                                     | *string*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |