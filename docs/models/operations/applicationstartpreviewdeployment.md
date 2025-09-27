# ApplicationStartPreviewDeployment

## Example Usage

```typescript
import { ApplicationStartPreviewDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationStartPreviewDeployment = {
  appName: "<value>",
  applicationId: "<id>",
  branch: "<value>",
  createdAt: "1713096026163",
  domainId: "<id>",
  expiresAt: "1755588697907",
  previewDeploymentId: "<id>",
  previewStatus: "done",
  pullRequestCommentId: "<id>",
  pullRequestId: "<id>",
  pullRequestNumber: "<value>",
  pullRequestTitle: "<value>",
  pullRequestURL: "https://kooky-cemetery.net/",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `branch`                                                                                             | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `domainId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `expiresAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `previewDeploymentId`                                                                                | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `previewStatus`                                                                                      | [operations.ApplicationStartPreviewStatus](../../models/operations/applicationstartpreviewstatus.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `pullRequestCommentId`                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `pullRequestId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `pullRequestNumber`                                                                                  | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `pullRequestTitle`                                                                                   | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `pullRequestURL`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |