# PostgresOneBackup

## Example Usage

```typescript
import { PostgresOneBackup } from "dokploy-sdk/models/operations";

let value: PostgresOneBackup = {
  appName: "<value>",
  backupId: "<id>",
  backupType: "database",
  composeId: "<id>",
  database: "<value>",
  databaseType: "mariadb",
  destinationId: "<id>",
  enabled: false,
  keepLatestCount: 1183.99,
  mariadbId: "<id>",
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

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `appName`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `backupId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `backupType`                                                                             | [operations.PostgresOneBackupType](../../models/operations/postgresonebackuptype.md)     | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `composeId`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `database`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `databaseType`                                                                           | [operations.PostgresOneDatabaseType](../../models/operations/postgresonedatabasetype.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `destinationId`                                                                          | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `enabled`                                                                                | *boolean*                                                                                | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `keepLatestCount`                                                                        | *number*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `mariadbId`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `metadata`                                                                               | *operations.PostgresOneMetadataUnion*                                                    | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `mongoId`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `mysqlId`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `postgresId`                                                                             | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `prefix`                                                                                 | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `schedule`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `serviceName`                                                                            | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `userId`                                                                                 | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |