# PostgresChangeStatusMount

## Example Usage

```typescript
import { PostgresChangeStatusMount } from "dokploy-sdk/models/operations";

let value: PostgresChangeStatusMount = {
  mountId: "<id>",
  type: "volume",
  hostPath: "<value>",
  volumeName: null,
  filePath: "/Network/brr_quash.mar",
  content: "<value>",
  serviceType: "mysql",
  mountPath: "<value>",
  applicationId: null,
  postgresId: "<id>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mysqlId: "<id>",
  redisId: null,
  composeId: "<id>",
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `mountId`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `type`                                                                                                   | [operations.PostgresChangeStatusType](../../models/operations/postgreschangestatustype.md)               | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `hostPath`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `volumeName`                                                                                             | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `filePath`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `content`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serviceType`                                                                                            | [operations.PostgresChangeStatusServiceType](../../models/operations/postgreschangestatusservicetype.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mountPath`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `applicationId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `postgresId`                                                                                             | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mariadbId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mongoId`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mysqlId`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `redisId`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `composeId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |