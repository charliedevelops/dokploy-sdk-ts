# DeploymentAllResponseBody

## Example Usage

```typescript
import { DeploymentAllResponseBody } from "dokploy-sdk/models/operations";

let value: DeploymentAllResponseBody = {
  deploymentId: "<id>",
  title: "<value>",
  description: null,
  status: "done",
  logPath: "<value>",
  pid: "<id>",
  applicationId: "<id>",
  composeId: null,
  serverId: "<id>",
  isPreviewDeployment: true,
  previewDeploymentId: "<id>",
  createdAt: "1728803025530",
  startedAt: "<value>",
  finishedAt: "<value>",
  errorMessage: null,
  scheduleId: "<id>",
  backupId: null,
  rollbackId: "<id>",
  volumeBackupId: "<id>",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `deploymentId`                                                                   | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `title`                                                                          | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `description`                                                                    | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `status`                                                                         | [operations.DeploymentAllStatus](../../models/operations/deploymentallstatus.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `logPath`                                                                        | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `pid`                                                                            | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `applicationId`                                                                  | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `composeId`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `serverId`                                                                       | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `isPreviewDeployment`                                                            | *boolean*                                                                        | :heavy_check_mark:                                                               | N/A                                                                              |
| `previewDeploymentId`                                                            | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `createdAt`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `startedAt`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `finishedAt`                                                                     | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `errorMessage`                                                                   | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `scheduleId`                                                                     | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `backupId`                                                                       | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `rollbackId`                                                                     | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `volumeBackupId`                                                                 | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |