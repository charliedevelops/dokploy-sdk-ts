# PostgresRemoveBackup

## Example Usage

```typescript
import { PostgresRemoveBackup } from "dokploy-sdk/models/operations";

let value: PostgresRemoveBackup = {
  backupId: "<id>",
  appName: "<value>",
  schedule: "<value>",
  enabled: false,
  database: "<value>",
  prefix: "<value>",
  serviceName: "<value>",
  destinationId: "<id>",
  keepLatestCount: 8878.45,
  backupType: "compose",
  databaseType: "mariadb",
  composeId: "<id>",
  postgresId: "<id>",
  mariadbId: null,
  mysqlId: null,
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
| `backupType`                                                                                   | [operations.PostgresRemoveBackupType](../../models/operations/postgresremovebackuptype.md)     | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `databaseType`                                                                                 | [operations.PostgresRemoveDatabaseType](../../models/operations/postgresremovedatabasetype.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `composeId`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `postgresId`                                                                                   | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mariadbId`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mysqlId`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `mongoId`                                                                                      | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `userId`                                                                                       | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `metadata`                                                                                     | *operations.PostgresRemoveMetadataUnion*                                                       | :heavy_minus_sign:                                                                             | N/A                                                                                            |