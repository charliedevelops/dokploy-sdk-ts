# ApplicationOneDeployment

## Example Usage

```typescript
import { ApplicationOneDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationOneDeployment = {
  deploymentId: "<id>",
  title: "<value>",
  description: "per freely distorted finally that",
  status: "running",
  logPath: "<value>",
  pid: "<id>",
  applicationId: "<id>",
  composeId: "<id>",
  serverId: "<id>",
  isPreviewDeployment: false,
  previewDeploymentId: "<id>",
  createdAt: "1719206842174",
  startedAt: null,
  finishedAt: "<value>",
  errorMessage: "<value>",
  scheduleId: "<id>",
  backupId: "<id>",
  rollbackId: "<id>",
  volumeBackupId: "<id>",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `deploymentId`                                                                     | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `title`                                                                            | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `description`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `status`                                                                           | [operations.ApplicationOneStatus](../../models/operations/applicationonestatus.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `logPath`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `pid`                                                                              | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `applicationId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `composeId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `serverId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `isPreviewDeployment`                                                              | *boolean*                                                                          | :heavy_check_mark:                                                                 | N/A                                                                                |
| `previewDeploymentId`                                                              | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `startedAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `finishedAt`                                                                       | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `errorMessage`                                                                     | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `scheduleId`                                                                       | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `backupId`                                                                         | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `rollbackId`                                                                       | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `volumeBackupId`                                                                   | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |