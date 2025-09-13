# BackupUpdateRequest

## Example Usage

```typescript
import { BackupUpdateRequest } from "dokploy-sdk/models/operations";

let value: BackupUpdateRequest = {
  backupId: "<id>",
  database: "<value>",
  databaseType: "mysql",
  destinationId: "<id>",
  prefix: "<value>",
  schedule: "<value>",
  serviceName: "<value>",
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `backupId`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `database`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `databaseType`                                                                             | [operations.BackupUpdateDatabaseType](../../models/operations/backupupdatedatabasetype.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `destinationId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `keepLatestCount`                                                                          | *number*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `metadata`                                                                                 | *any*                                                                                      | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `prefix`                                                                                   | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `schedule`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `serviceName`                                                                              | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |