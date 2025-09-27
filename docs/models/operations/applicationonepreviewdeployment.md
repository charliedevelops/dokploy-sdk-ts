# ApplicationOnePreviewDeployment

## Example Usage

```typescript
import { ApplicationOnePreviewDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationOnePreviewDeployment = {
  appName: "<value>",
  applicationId: "<id>",
  branch: "<value>",
  createdAt: "1721541727814",
  domainId: "<id>",
  expiresAt: "1758365407340",
  previewDeploymentId: "<id>",
  previewStatus: "running",
  pullRequestCommentId: "<id>",
  pullRequestId: "<id>",
  pullRequestNumber: "<value>",
  pullRequestTitle: "<value>",
  pullRequestURL: "https://turbulent-reconsideration.net/",
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `appName`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `branch`                                                                                         | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `domainId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `expiresAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `previewDeploymentId`                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `previewStatus`                                                                                  | [operations.ApplicationOnePreviewStatus](../../models/operations/applicationonepreviewstatus.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pullRequestCommentId`                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pullRequestId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pullRequestNumber`                                                                              | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pullRequestTitle`                                                                               | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pullRequestURL`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |