# ApplicationStopPreviewDeployment

## Example Usage

```typescript
import { ApplicationStopPreviewDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationStopPreviewDeployment = {
  previewDeploymentId: "<id>",
  branch: "<value>",
  pullRequestId: "<id>",
  pullRequestNumber: "<value>",
  pullRequestURL: "https://wordy-lotion.com",
  pullRequestTitle: "<value>",
  pullRequestCommentId: "<id>",
  previewStatus: "done",
  appName: "<value>",
  applicationId: "<id>",
  domainId: "<id>",
  createdAt: "1726706238926",
  expiresAt: "1741867234472",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `previewDeploymentId`                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `branch`                                                                                           | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pullRequestId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pullRequestNumber`                                                                                | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pullRequestURL`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pullRequestTitle`                                                                                 | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `pullRequestCommentId`                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `previewStatus`                                                                                    | [operations.ApplicationStopPreviewStatus](../../models/operations/applicationstoppreviewstatus.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `appName`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `applicationId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `domainId`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `expiresAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |