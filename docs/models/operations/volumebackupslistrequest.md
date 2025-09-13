# VolumeBackupsListRequest

## Example Usage

```typescript
import { VolumeBackupsListRequest } from "dokploy-sdk/models/operations";

let value: VolumeBackupsListRequest = {
  id: "<id>",
  volumeBackupType: "mariadb",
};
```

## Fields

| Field                                                                      | Type                                                                       | Required                                                                   | Description                                                                |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| `id`                                                                       | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `volumeBackupType`                                                         | [operations.VolumeBackupType](../../models/operations/volumebackuptype.md) | :heavy_check_mark:                                                         | N/A                                                                        |