# PreviewDeploymentAllResponseBody

## Example Usage

```typescript
import { PreviewDeploymentAllResponseBody } from "dokploy-sdk/models/operations";

let value: PreviewDeploymentAllResponseBody = {
  previewDeploymentId: "<id>",
  branch: "<value>",
  pullRequestId: "<id>",
  pullRequestNumber: "<value>",
  pullRequestURL: "https://gloomy-bench.name/",
  pullRequestTitle: "<value>",
  pullRequestCommentId: "<id>",
  previewStatus: "error",
  appName: "<value>",
  applicationId: "<id>",
  domainId: "<id>",
  createdAt: "1709805103002",
  expiresAt: "1766781456364",
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `previewDeploymentId`                                                                                        | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `branch`                                                                                                     | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `pullRequestId`                                                                                              | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `pullRequestNumber`                                                                                          | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `pullRequestURL`                                                                                             | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `pullRequestTitle`                                                                                           | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `pullRequestCommentId`                                                                                       | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `previewStatus`                                                                                              | [operations.PreviewDeploymentAllPreviewStatus](../../models/operations/previewdeploymentallpreviewstatus.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `appName`                                                                                                    | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `applicationId`                                                                                              | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `domainId`                                                                                                   | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `createdAt`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `expiresAt`                                                                                                  | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |