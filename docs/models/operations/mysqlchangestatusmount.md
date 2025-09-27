# MysqlChangeStatusMount

## Example Usage

```typescript
import { MysqlChangeStatusMount } from "dokploy-sdk/models/operations";

let value: MysqlChangeStatusMount = {
  applicationId: null,
  composeId: "<id>",
  content: "<value>",
  filePath: "/boot/defaults/afore_tool.csh",
  hostPath: "<value>",
  mariadbId: "<id>",
  mongoId: "<id>",
  mountId: "<id>",
  mountPath: "<value>",
  mysqlId: null,
  postgresId: "<id>",
  redisId: "<id>",
  serviceType: "redis",
  type: "volume",
  volumeName: "<value>",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `composeId`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `content`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `filePath`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `hostPath`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mariadbId`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mongoId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mountId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mountPath`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mysqlId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `postgresId`                                                                                       | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `redisId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serviceType`                                                                                      | [operations.MysqlChangeStatusServiceType](../../models/operations/mysqlchangestatusservicetype.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `type`                                                                                             | [operations.MysqlChangeStatusType](../../models/operations/mysqlchangestatustype.md)               | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `volumeName`                                                                                       | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |