# PostgresDeployBackup

## Example Usage

```typescript
import { PostgresDeployBackup } from "dokploy-sdk/models/operations";

let value: PostgresDeployBackup = {
  appName: "<value>",
  backupId: "<id>",
  backupType: "database",
  composeId: "<id>",
  database: "<value>",
  databaseType: "mysql",
  destinationId: "<id>",
  enabled: null,
  keepLatestCount: 3696.38,
  mariadbId: null,
  mongoId: "<id>",
  mysqlId: "<id>",
  postgresId: "<id>",
  prefix: "<value>",
  schedule: "<value>",
  serviceName: "<value>",
  userId: "<id>",
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `appName`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `backupId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `backupType`                                                                                   | [operations.PostgresDeployBackupType](../../models/operations/postgresdeploybackuptype.md)     | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `composeId`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `database`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `databaseType`                                                                                 | [operations.PostgresDeployDatabaseType](../../models/operations/postgresdeploydatabasetype.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `destinationId`                                                                                | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `enabled`                                                                                      | *boolean*                                                                                      | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `keepLatestCount`                                                                              | *number*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mariadbId`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `metadata`                                                                                     | *operations.PostgresDeployMetadataUnion*                                                       | :heavy_minus_sign:                                                                             | N/A                                                                                            |
| `mongoId`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mysqlId`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `postgresId`                                                                                   | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `prefix`                                                                                       | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `schedule`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serviceName`                                                                                  | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `userId`                                                                                       | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |