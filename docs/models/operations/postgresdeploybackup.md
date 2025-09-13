# PostgresDeployBackup

## Example Usage

```typescript
import { PostgresDeployBackup } from "dokploy-sdk/models/operations";

let value: PostgresDeployBackup = {
  backupId: "<id>",
  appName: "<value>",
  schedule: "<value>",
  enabled: null,
  database: "<value>",
  prefix: "<value>",
  serviceName: "<value>",
  destinationId: "<id>",
  keepLatestCount: 277.18,
  backupType: "compose",
  databaseType: "mariadb",
  composeId: null,
  postgresId: "<id>",
  mariadbId: "<id>",
  mysqlId: "<id>",
  mongoId: "<id>",
  userId: "<id>",
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `backupId`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `appName`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `schedule`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `enabled`                                                                                      | *boolean*                                                                                      | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `database`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `prefix`                                                                                       | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serviceName`                                                                                  | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `destinationId`                                                                                | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `keepLatestCount`                                                                              | *number*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `backupType`                                                                                   | [operations.PostgresDeployBackupType](../../models/operations/postgresdeploybackuptype.md)     | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `databaseType`                                                                                 | [operations.PostgresDeployDatabaseType](../../models/operations/postgresdeploydatabasetype.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `composeId`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `postgresId`                                                                                   | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mariadbId`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mysqlId`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mongoId`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `userId`                                                                                       | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `metadata`                                                                                     | *operations.PostgresDeployMetadataUnion*                                                       | :heavy_minus_sign:                                                                             | N/A                                                                                            |