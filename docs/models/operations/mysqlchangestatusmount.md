# MysqlChangeStatusMount

## Example Usage

```typescript
import { MysqlChangeStatusMount } from "dokploy-sdk/models/operations";

let value: MysqlChangeStatusMount = {
  mountId: "<id>",
  type: "bind",
  hostPath: "<value>",
  volumeName: "<value>",
  filePath: "/boot/defaults/afore_tool.csh",
  content: "<value>",
  serviceType: "mysql",
  mountPath: "<value>",
  applicationId: "<id>",
  postgresId: null,
  mariadbId: "<id>",
  mongoId: "<id>",
  mysqlId: "<id>",
  redisId: "<id>",
  composeId: "<id>",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `mountId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `type`                                                                                             | [operations.MysqlChangeStatusType](../../models/operations/mysqlchangestatustype.md)               | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `hostPath`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `volumeName`                                                                                       | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `filePath`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `content`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serviceType`                                                                                      | [operations.MysqlChangeStatusServiceType](../../models/operations/mysqlchangestatusservicetype.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mountPath`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `postgresId`                                                                                       | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mariadbId`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mongoId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `mysqlId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `redisId`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `composeId`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |