# ApplicationStartDeployment

## Example Usage

```typescript
import { ApplicationStartDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationStartDeployment = {
  deploymentId: "<id>",
  title: "<value>",
  description: "minus the outlying phew sternly",
  status: null,
  logPath: "<value>",
  pid: "<id>",
  applicationId: "<id>",
  composeId: "<id>",
  serverId: "<id>",
  isPreviewDeployment: false,
  previewDeploymentId: "<id>",
  createdAt: "1704851529165",
  startedAt: null,
  finishedAt: null,
  errorMessage: null,
  scheduleId: "<id>",
  backupId: null,
  rollbackId: "<id>",
  volumeBackupId: "<id>",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `deploymentId`                                                                         | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `title`                                                                                | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `description`                                                                          | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `status`                                                                               | [operations.ApplicationStartStatus](../../models/operations/applicationstartstatus.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `logPath`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `pid`                                                                                  | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `applicationId`                                                                        | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `composeId`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `serverId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `isPreviewDeployment`                                                                  | *boolean*                                                                              | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `previewDeploymentId`                                                                  | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `createdAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `startedAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `finishedAt`                                                                           | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `errorMessage`                                                                         | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `scheduleId`                                                                           | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `backupId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `rollbackId`                                                                           | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `volumeBackupId`                                                                       | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |