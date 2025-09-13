# PostgresChangeStatusMount

## Example Usage

```typescript
import { PostgresChangeStatusMount } from "dokploy-sdk/models/operations";

let value: PostgresChangeStatusMount = {
  applicationId: "<id>",
  composeId: "<id>",
  content: null,
  filePath: "/Network/brr_quash.mar",
  hostPath: "<value>",
  mariadbId: "<id>",
  mongoId: null,
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: "<id>",
  postgresId: "<id>",
  redisId: "<id>",
  serviceType: "redis",
  type: "bind",
  volumeName: "<value>",
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `composeId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `content`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `filePath`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `hostPath`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mariadbId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mongoId`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mountId`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mountPath`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mysqlId`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `postgresId`                                                                                             | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `redisId`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serviceType`                                                                                            | [operations.PostgresChangeStatusServiceType](../../models/operations/postgreschangestatusservicetype.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `type`                                                                                                   | [operations.PostgresChangeStatusType](../../models/operations/postgreschangestatustype.md)               | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `volumeName`                                                                                             | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |