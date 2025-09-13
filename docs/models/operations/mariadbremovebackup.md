# MariadbRemoveBackup

## Example Usage

```typescript
import { MariadbRemoveBackup } from "dokploy-sdk/models/operations";

let value: MariadbRemoveBackup = {
  backupId: "<id>",
  appName: "<value>",
  schedule: "<value>",
  enabled: true,
  database: "<value>",
  prefix: "<value>",
  serviceName: "<value>",
  destinationId: "<id>",
  keepLatestCount: null,
  backupType: "compose",
  databaseType: "mongo",
  composeId: "<id>",
  postgresId: "<id>",
  mariadbId: "<id>",
  mysqlId: "<id>",
  mongoId: "<id>",
  userId: "<id>",
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `backupId`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `appName`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `schedule`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `database`                                                                                   | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `prefix`                                                                                     | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `serviceName`                                                                                | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `destinationId`                                                                              | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `keepLatestCount`                                                                            | *number*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `backupType`                                                                                 | [operations.MariadbRemoveBackupType](../../models/operations/mariadbremovebackuptype.md)     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `databaseType`                                                                               | [operations.MariadbRemoveDatabaseType](../../models/operations/mariadbremovedatabasetype.md) | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `composeId`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `postgresId`                                                                                 | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mariadbId`                                                                                  | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mysqlId`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `mongoId`                                                                                    | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `userId`                                                                                     | *string*                                                                                     | :heavy_check_mark:                                                                           | N/A                                                                                          |
| `metadata`                                                                                   | *operations.MariadbRemoveMetadataUnion*                                                      | :heavy_minus_sign:                                                                           | N/A                                                                                          |