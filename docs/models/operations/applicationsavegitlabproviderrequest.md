# ApplicationSaveGitlabProviderRequest

## Example Usage

```typescript
import { ApplicationSaveGitlabProviderRequest } from "dokploy-sdk/models/operations";

let value: ApplicationSaveGitlabProviderRequest = {
  applicationId: "<id>",
  gitlabBranch: "<value>",
  gitlabBuildPath: "<value>",
  gitlabOwner: "<value>",
  gitlabRepository: "<value>",
  gitlabId: "<id>",
  gitlabProjectId: 9227.42,
  gitlabPathNamespace: "<value>",
  enableSubmodules: true,
};
```

## Fields

| Field                 | Type                  | Required              | Description           |
| --------------------- | --------------------- | --------------------- | --------------------- |
| `applicationId`       | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabBranch`        | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabBuildPath`     | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabOwner`         | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabRepository`    | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabId`            | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabProjectId`     | *number*              | :heavy_check_mark:    | N/A                   |
| `gitlabPathNamespace` | *string*              | :heavy_check_mark:    | N/A                   |
| `watchPaths`          | *string*[]            | :heavy_minus_sign:    | N/A                   |
| `enableSubmodules`    | *boolean*             | :heavy_check_mark:    | N/A                   |