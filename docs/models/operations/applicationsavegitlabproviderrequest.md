# ApplicationSaveGitlabProviderRequest

## Example Usage

```typescript
import { ApplicationSaveGitlabProviderRequest } from "dokploy-sdk/models/operations";

let value: ApplicationSaveGitlabProviderRequest = {
  applicationId: "<id>",
  enableSubmodules: false,
  gitlabBranch: "<value>",
  gitlabBuildPath: "<value>",
  gitlabId: "<id>",
  gitlabOwner: "<value>",
  gitlabPathNamespace: "<value>",
  gitlabProjectId: 1065.84,
  gitlabRepository: "<value>",
};
```

## Fields

| Field                 | Type                  | Required              | Description           |
| --------------------- | --------------------- | --------------------- | --------------------- |
| `applicationId`       | *string*              | :heavy_check_mark:    | N/A                   |
| `enableSubmodules`    | *boolean*             | :heavy_check_mark:    | N/A                   |
| `gitlabBranch`        | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabBuildPath`     | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabId`            | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabOwner`         | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabPathNamespace` | *string*              | :heavy_check_mark:    | N/A                   |
| `gitlabProjectId`     | *number*              | :heavy_check_mark:    | N/A                   |
| `gitlabRepository`    | *string*              | :heavy_check_mark:    | N/A                   |
| `watchPaths`          | *string*[]            | :heavy_minus_sign:    | N/A                   |