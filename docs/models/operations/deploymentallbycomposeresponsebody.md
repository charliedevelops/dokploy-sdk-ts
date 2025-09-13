# DeploymentAllByComposeResponseBody

## Example Usage

```typescript
import { DeploymentAllByComposeResponseBody } from "dokploy-sdk/models/operations";

let value: DeploymentAllByComposeResponseBody = {
  applicationId: "<id>",
  backupId: "<id>",
  composeId: "<id>",
  createdAt: "1725879023687",
  deploymentId: "<id>",
  description: "apricot elegant oof",
  errorMessage: "<value>",
  finishedAt: "<value>",
  isPreviewDeployment: false,
  logPath: "<value>",
  pid: "<id>",
  previewDeploymentId: "<id>",
  rollbackId: "<id>",
  scheduleId: "<id>",
  serverId: "<id>",
  startedAt: "<value>",
  status: "error",
  title: "<value>",
  volumeBackupId: "<id>",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `applicationId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `backupId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `composeId`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `deploymentId`                                                                                     | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `errorMessage`                                                                                     | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `finishedAt`                                                                                       | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `isPreviewDeployment`                                                                              | *boolean*                                                                                          | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `logPath`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pid`                                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `previewDeploymentId`                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `rollbackId`                                                                                       | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `scheduleId`                                                                                       | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `serverId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `startedAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `status`                                                                                           | [operations.DeploymentAllByComposeStatus](../../models/operations/deploymentallbycomposestatus.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `title`                                                                                            | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `volumeBackupId`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |