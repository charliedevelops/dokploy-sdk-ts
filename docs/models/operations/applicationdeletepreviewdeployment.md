# ApplicationDeletePreviewDeployment

## Example Usage

```typescript
import { ApplicationDeletePreviewDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationDeletePreviewDeployment = {
  previewDeploymentId: "<id>",
  branch: "<value>",
  pullRequestId: "<id>",
  pullRequestNumber: "<value>",
  pullRequestURL: "https://multicolored-fuel.net",
  pullRequestTitle: "<value>",
  pullRequestCommentId: "<id>",
  previewStatus: "idle",
  appName: "<value>",
  applicationId: "<id>",
  domainId: "<id>",
  createdAt: "1726843521464",
  expiresAt: "1749050316538",
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `previewDeploymentId`                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `branch`                                                                                               | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `pullRequestId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `pullRequestNumber`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `pullRequestURL`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `pullRequestTitle`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `pullRequestCommentId`                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `previewStatus`                                                                                        | [operations.ApplicationDeletePreviewStatus](../../models/operations/applicationdeletepreviewstatus.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `domainId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `expiresAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |