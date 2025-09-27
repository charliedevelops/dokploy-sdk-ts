# UserUpdateMetricsConfig

## Example Usage

```typescript
import { UserUpdateMetricsConfig } from "dokploy-sdk/models/operations";

let value: UserUpdateMetricsConfig = {
  containers: {
    refreshRate: 9323.07,
    services: {
      exclude: [],
      include: [
        "<value 1>",
        "<value 2>",
      ],
    },
  },
  server: {
    cronJob: "<value>",
    port: 8682.08,
    refreshRate: 9187.96,
    retentionDays: 6761.54,
    thresholds: {
      cpu: 7663.31,
      memory: 5312.52,
    },
    token: "<value>",
    type: "Remote",
    urlCallback: "<value>",
  },
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `containers`                                                                       | [operations.UserUpdateContainers](../../models/operations/userupdatecontainers.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `server`                                                                           | [operations.UserUpdateServer](../../models/operations/userupdateserver.md)         | :heavy_check_mark:                                                                 | N/A                                                                                |