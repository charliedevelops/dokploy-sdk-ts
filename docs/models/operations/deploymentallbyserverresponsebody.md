# DeploymentAllByServerResponseBody

## Example Usage

```typescript
import { DeploymentAllByServerResponseBody } from "dokploy-sdk/models/operations";

let value: DeploymentAllByServerResponseBody = {
  deploymentId: "<id>",
  title: "<value>",
  description:
    "baritone making apropos beside mad underneath past than obligation strictly",
  status: "error",
  logPath: "<value>",
  pid: "<id>",
  applicationId: "<id>",
  composeId: "<id>",
  serverId: null,
  isPreviewDeployment: true,
  previewDeploymentId: "<id>",
  createdAt: "1714883734464",
  startedAt: "<value>",
  finishedAt: "<value>",
  errorMessage: "<value>",
  scheduleId: null,
  backupId: "<id>",
  rollbackId: "<id>",
  volumeBackupId: null,
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `deploymentId`                                                                                   | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `title`                                                                                          | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `status`                                                                                         | [operations.DeploymentAllByServerStatus](../../models/operations/deploymentallbyserverstatus.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `logPath`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pid`                                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `composeId`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `serverId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `isPreviewDeployment`                                                                            | *boolean*                                                                                        | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `previewDeploymentId`                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `startedAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `finishedAt`                                                                                     | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `errorMessage`                                                                                   | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `scheduleId`                                                                                     | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `backupId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `rollbackId`                                                                                     | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `volumeBackupId`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |