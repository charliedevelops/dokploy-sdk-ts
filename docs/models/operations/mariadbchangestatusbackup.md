# MariadbChangeStatusBackup

## Example Usage

```typescript
import { MariadbChangeStatusBackup } from "dokploy-sdk/models/operations";

let value: MariadbChangeStatusBackup = {
  appName: "<value>",
  backupId: "<id>",
  backupType: "compose",
  composeId: null,
  database: "<value>",
  databaseType: "web-server",
  destinationId: "<id>",
  enabled: true,
  keepLatestCount: 2948.61,
  mariadbId: "<id>",
  mongoId: "<id>",
  mysqlId: null,
  postgresId: "<id>",
  prefix: "<value>",
  schedule: "<value>",
  serviceName: "<value>",
  userId: "<id>",
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `appName`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `backupId`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `backupType`                                                                                             | [operations.MariadbChangeStatusBackupType](../../models/operations/mariadbchangestatusbackuptype.md)     | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `composeId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `database`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `databaseType`                                                                                           | [operations.MariadbChangeStatusDatabaseType](../../models/operations/mariadbchangestatusdatabasetype.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `destinationId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `enabled`                                                                                                | *boolean*                                                                                                | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `keepLatestCount`                                                                                        | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mariadbId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `metadata`                                                                                               | *operations.MariadbChangeStatusMetadataUnion*                                                            | :heavy_minus_sign:                                                                                       | N/A                                                                                                      |
| `mongoId`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `mysqlId`                                                                                                | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `postgresId`                                                                                             | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `prefix`                                                                                                 | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `schedule`                                                                                               | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `serviceName`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `userId`                                                                                                 | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |