# MysqlOneBackup

## Example Usage

```typescript
import { MysqlOneBackup } from "dokploy-sdk/models/operations";

let value: MysqlOneBackup = {
  appName: "<value>",
  backupId: "<id>",
  backupType: "compose",
  composeId: "<id>",
  database: "<value>",
  databaseType: "postgres",
  destinationId: "<id>",
  enabled: null,
  keepLatestCount: 8941.06,
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

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `appName`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `backupId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `backupType`                                                                       | [operations.MysqlOneBackupType](../../models/operations/mysqlonebackuptype.md)     | :heavy_check_mark:                                                                 | N/A                                                                                |
| `composeId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `database`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `databaseType`                                                                     | [operations.MysqlOneDatabaseType](../../models/operations/mysqlonedatabasetype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `destinationId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enabled`                                                                          | *boolean*                                                                          | :heavy_check_mark:                                                                 | N/A                                                                                |
| `keepLatestCount`                                                                  | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `mariadbId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `metadata`                                                                         | *operations.MysqlOneMetadataUnion*                                                 | :heavy_minus_sign:                                                                 | N/A                                                                                |
| `mongoId`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `mysqlId`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `postgresId`                                                                       | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `prefix`                                                                           | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `schedule`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serviceName`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `userId`                                                                           | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |