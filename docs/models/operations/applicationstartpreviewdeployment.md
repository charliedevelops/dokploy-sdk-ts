# ApplicationStartPreviewDeployment

## Example Usage

```typescript
import { ApplicationStartPreviewDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationStartPreviewDeployment = {
  previewDeploymentId: "<id>",
  branch: "<value>",
  pullRequestId: "<id>",
  pullRequestNumber: "<value>",
  pullRequestURL: "https://late-maestro.name/",
  pullRequestTitle: "<value>",
  pullRequestCommentId: "<id>",
  previewStatus: "done",
  appName: "<value>",
  applicationId: "<id>",
  domainId: null,
  createdAt: "1718432476606",
  expiresAt: "1760340036139",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `previewDeploymentId`                                                                                | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `branch`                                                                                             | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `pullRequestId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `pullRequestNumber`                                                                                  | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `pullRequestURL`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `pullRequestTitle`                                                                                   | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `pullRequestCommentId`                                                                               | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `previewStatus`                                                                                      | [operations.ApplicationStartPreviewStatus](../../models/operations/applicationstartpreviewstatus.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `appName`                                                                                            | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `applicationId`                                                                                      | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `domainId`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `expiresAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |