# ApplicationStopPreviewDeployment

## Example Usage

```typescript
import { ApplicationStopPreviewDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationStopPreviewDeployment = {
  appName: "<value>",
  applicationId: "<id>",
  branch: "<value>",
  createdAt: "1724899117402",
  domainId: "<id>",
  expiresAt: "1738830187880",
  previewDeploymentId: "<id>",
  previewStatus: "done",
  pullRequestCommentId: "<id>",
  pullRequestId: "<id>",
  pullRequestNumber: "<value>",
  pullRequestTitle: "<value>",
  pullRequestURL: "https://second-flat.biz/",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `branch`                                                                                           | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `domainId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `expiresAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `previewDeploymentId`                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `previewStatus`                                                                                    | [operations.ApplicationStopPreviewStatus](../../models/operations/applicationstoppreviewstatus.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pullRequestCommentId`                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pullRequestId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pullRequestNumber`                                                                                | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pullRequestTitle`                                                                                 | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pullRequestURL`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |