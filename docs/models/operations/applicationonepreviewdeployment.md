# ApplicationOnePreviewDeployment

## Example Usage

```typescript
import { ApplicationOnePreviewDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationOnePreviewDeployment = {
  previewDeploymentId: "<id>",
  branch: "<value>",
  pullRequestId: "<id>",
  pullRequestNumber: "<value>",
  pullRequestURL: "https://palatable-palate.net",
  pullRequestTitle: "<value>",
  pullRequestCommentId: "<id>",
  previewStatus: "running",
  appName: "<value>",
  applicationId: "<id>",
  domainId: "<id>",
  createdAt: "1731743435083",
  expiresAt: "1761043069810",
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `previewDeploymentId`                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `branch`                                                                                         | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pullRequestId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pullRequestNumber`                                                                              | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pullRequestURL`                                                                                 | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pullRequestTitle`                                                                               | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `pullRequestCommentId`                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `previewStatus`                                                                                  | [operations.ApplicationOnePreviewStatus](../../models/operations/applicationonepreviewstatus.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `appName`                                                                                        | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `applicationId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `domainId`                                                                                       | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `expiresAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |