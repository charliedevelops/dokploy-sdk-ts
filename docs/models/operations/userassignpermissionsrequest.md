# UserAssignPermissionsRequest

## Example Usage

```typescript
import { UserAssignPermissionsRequest } from "dokploy-sdk/models/operations";

let value: UserAssignPermissionsRequest = {
  id: "<id>",
  accessedProjects: [
    "<value 1>",
  ],
  accessedEnvironments: [
    "<value 1>",
    "<value 2>",
  ],
  accessedServices: [
    "<value 1>",
  ],
  canCreateProjects: true,
  canCreateServices: true,
  canDeleteProjects: true,
  canDeleteServices: true,
  canAccessToDocker: false,
  canAccessToTraefikFiles: false,
  canAccessToAPI: false,
  canAccessToSSHKeys: true,
  canAccessToGitProviders: true,
};
```

## Fields

| Field                     | Type                      | Required                  | Description               |
| ------------------------- | ------------------------- | ------------------------- | ------------------------- |
| `id`                      | *string*                  | :heavy_check_mark:        | N/A                       |
| `accessedProjects`        | *string*[]                | :heavy_check_mark:        | N/A                       |
| `accessedEnvironments`    | *string*[]                | :heavy_check_mark:        | N/A                       |
| `accessedServices`        | *string*[]                | :heavy_check_mark:        | N/A                       |
| `canCreateProjects`       | *boolean*                 | :heavy_check_mark:        | N/A                       |
| `canCreateServices`       | *boolean*                 | :heavy_check_mark:        | N/A                       |
| `canDeleteProjects`       | *boolean*                 | :heavy_check_mark:        | N/A                       |
| `canDeleteServices`       | *boolean*                 | :heavy_check_mark:        | N/A                       |
| `canAccessToDocker`       | *boolean*                 | :heavy_check_mark:        | N/A                       |
| `canAccessToTraefikFiles` | *boolean*                 | :heavy_check_mark:        | N/A                       |
| `canAccessToAPI`          | *boolean*                 | :heavy_check_mark:        | N/A                       |
| `canAccessToSSHKeys`      | *boolean*                 | :heavy_check_mark:        | N/A                       |
| `canAccessToGitProviders` | *boolean*                 | :heavy_check_mark:        | N/A                       |