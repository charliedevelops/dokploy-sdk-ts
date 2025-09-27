# ApplicationDeletePreviewDeployment

## Example Usage

```typescript
import { ApplicationDeletePreviewDeployment } from "dokploy-sdk/models/operations";

let value: ApplicationDeletePreviewDeployment = {
  appName: "<value>",
  applicationId: "<id>",
  branch: "<value>",
  createdAt: "1731265642532",
  domainId: "<id>",
  expiresAt: "1759385051799",
  previewDeploymentId: "<id>",
  previewStatus: "idle",
  pullRequestCommentId: "<id>",
  pullRequestId: "<id>",
  pullRequestNumber: "<value>",
  pullRequestTitle: "<value>",
  pullRequestURL: "https://self-assured-underpants.info/",
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `appName`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `applicationId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `branch`                                                                                               | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `domainId`                                                                                             | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `expiresAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `previewDeploymentId`                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `previewStatus`                                                                                        | [operations.ApplicationDeletePreviewStatus](../../models/operations/applicationdeletepreviewstatus.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `pullRequestCommentId`                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `pullRequestId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `pullRequestNumber`                                                                                    | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `pullRequestTitle`                                                                                     | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `pullRequestURL`                                                                                       | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |