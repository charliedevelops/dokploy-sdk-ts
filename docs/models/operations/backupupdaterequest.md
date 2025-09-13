# BackupUpdateRequest

## Example Usage

```typescript
import { BackupUpdateRequest } from "dokploy-sdk/models/operations";

let value: BackupUpdateRequest = {
  schedule: "<value>",
  prefix: "<value>",
  backupId: "<id>",
  destinationId: "<id>",
  database: "<value>",
  serviceName: "<value>",
  databaseType: "web-server",
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `schedule`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `prefix`                                                                                   | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `backupId`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `destinationId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `database`                                                                                 | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `keepLatestCount`                                                                          | *number*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `serviceName`                                                                              | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `metadata`                                                                                 | *any*                                                                                      | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `databaseType`                                                                             | [operations.BackupUpdateDatabaseType](../../models/operations/backupupdatedatabasetype.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |