# MysqlChangeStatusBackup

## Example Usage

```typescript
import { MysqlChangeStatusBackup } from "dokploy-sdk/models/operations";

let value: MysqlChangeStatusBackup = {
  appName: "<value>",
  backupId: "<id>",
  backupType: "compose",
  composeId: "<id>",
  database: "<value>",
  databaseType: "web-server",
  destinationId: "<id>",
  enabled: true,
  keepLatestCount: 7544.99,
  mariadbId: "<id>",
  mongoId: "<id>",
  mysqlId: "<id>",
  postgresId: "<id>",
  prefix: "<value>",
  schedule: "<value>",
  serviceName: null,
  userId: "<id>",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `backupId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `backupType`                                                                                         | [operations.MysqlChangeStatusBackupType](../../models/operations/mysqlchangestatusbackuptype.md)     | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `composeId`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `database`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `databaseType`                                                                                       | [operations.MysqlChangeStatusDatabaseType](../../models/operations/mysqlchangestatusdatabasetype.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `destinationId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `enabled`                                                                                            | *boolean*                                                                                            | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `keepLatestCount`                                                                                    | *number*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mariadbId`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `metadata`                                                                                           | *operations.MysqlChangeStatusMetadataUnion*                                                          | :heavy_minus_sign:                                                                                   | N/A                                                                                                  |
| `mongoId`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `mysqlId`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `postgresId`                                                                                         | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `prefix`                                                                                             | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `schedule`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `serviceName`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `userId`                                                                                             | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |