# UserUpdateMetricsConfig

## Example Usage

```typescript
import { UserUpdateMetricsConfig } from "dokploy-sdk/models/operations";

let value: UserUpdateMetricsConfig = {
  server: {
    type: "Remote",
    refreshRate: 8682.08,
    port: 9187.96,
    token: "<value>",
    urlCallback: "<value>",
    retentionDays: 6761.54,
    cronJob: "<value>",
    thresholds: {
      cpu: 5312.52,
      memory: 790.33,
    },
  },
  containers: {
    refreshRate: 5685.29,
    services: {
      include: [],
      exclude: [
        "<value 1>",
        "<value 2>",
      ],
    },
  },
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `server`                                                                           | [operations.UserUpdateServer](../../models/operations/userupdateserver.md)         | :heavy_check_mark:                                                                 | N/A                                                                                |
| `containers`                                                                       | [operations.UserUpdateContainers](../../models/operations/userupdatecontainers.md) | :heavy_check_mark:                                                                 | N/A                                                                                |