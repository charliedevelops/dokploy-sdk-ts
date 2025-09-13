# ProjectAllResponseBody

## Example Usage

```typescript
import { ProjectAllResponseBody } from "dokploy-sdk/models/operations";

let value: ProjectAllResponseBody = {
  createdAt: "1727372081295",
  description: "twin rue deliberately next fumigate near",
  env: "<value>",
  environments: [
    {
      createdAt: "1714731351944",
      description: "gee around next evenly",
      env: "<value>",
      environmentId: "<id>",
      name: "<value>",
      projectId: "<id>",
    },
  ],
  name: "<value>",
  organizationId: "<id>",
  projectId: "<id>",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `createdAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `description`                                                                          | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `env`                                                                                  | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `environments`                                                                         | [operations.ProjectAllEnvironment](../../models/operations/projectallenvironment.md)[] | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `name`                                                                                 | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `organizationId`                                                                       | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `projectId`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |