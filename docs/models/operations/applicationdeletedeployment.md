# ApplicationDeleteDeployment

## Example Usage

```typescript
import { ApplicationDeleteDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteDeployment = {
  deploymentId: "<id>",
  title: "<value>",
  description: "genuine parody jovially obediently",
  status: "done",
  logPath: "<value>",
  pid: "<id>",
  applicationId: null,
  composeId: "<id>",
  serverId: "<id>",
  isPreviewDeployment: false,
  previewDeploymentId: null,
  createdAt: "1722197404573",
  startedAt: "<value>",
  finishedAt: "<value>",
  errorMessage: "<value>",
  scheduleId: "<id>",
  backupId: "<id>",
  rollbackId: "<id>",
  volumeBackupId: "<id>",
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `deploymentId`                                                                           | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `title`                                                                                  | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `description`                                                                            | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `status`                                                                                 | [operations.ApplicationDeleteStatus](../../models/operations/applicationdeletestatus.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `logPath`                                                                                | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `pid`                                                                                    | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `applicationId`                                                                          | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `composeId`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `serverId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `isPreviewDeployment`                                                                    | *boolean*                                                                                | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `previewDeploymentId`                                                                    | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `createdAt`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `startedAt`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `finishedAt`                                                                             | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `errorMessage`                                                                           | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `scheduleId`                                                                             | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `backupId`                                                                               | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `rollbackId`                                                                             | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `volumeBackupId`                                                                         | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |