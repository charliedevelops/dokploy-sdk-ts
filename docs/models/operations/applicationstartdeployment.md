# ApplicationStartDeployment

## Example Usage

```typescript
import { ApplicationStartDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationStartDeployment = {
  applicationId: "<id>",
  backupId: "<id>",
  composeId: "<id>",
  createdAt: "1721677454446",
  deploymentId: "<id>",
  description: "an ideal a without likewise phooey hm",
  errorMessage: "<value>",
  finishedAt: "<value>",
  isPreviewDeployment: true,
  logPath: "<value>",
  pid: "<id>",
  previewDeploymentId: "<id>",
  rollbackId: "<id>",
  scheduleId: "<id>",
  serverId: "<id>",
  startedAt: null,
  status: "error",
  title: "<value>",
  volumeBackupId: null,
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `applicationId`                                                                        | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `backupId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `composeId`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `createdAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `deploymentId`                                                                         | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `description`                                                                          | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `errorMessage`                                                                         | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `finishedAt`                                                                           | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `isPreviewDeployment`                                                                  | *boolean*                                                                              | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `logPath`                                                                              | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `pid`                                                                                  | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `previewDeploymentId`                                                                  | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `rollbackId`                                                                           | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `scheduleId`                                                                           | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `serverId`                                                                             | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `startedAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `status`                                                                               | [operations.ApplicationStartStatus](../../models/operations/applicationstartstatus.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `title`                                                                                | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `volumeBackupId`                                                                       | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |