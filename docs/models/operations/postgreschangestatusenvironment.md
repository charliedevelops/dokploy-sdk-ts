# PostgresChangeStatusEnvironment

## Example Usage

```typescript
import { PostgresChangeStatusEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresChangeStatusEnvironment = {
  createdAt: "1730185612778",
  description: "redact provided tut yahoo",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1725186984913",
    description: "gosh hexagon giggle carefully spear abaft meander",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
  projectId: "<id>",
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `env`                                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `environmentId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `project`                                                                                        | [operations.PostgresChangeStatusProject](../../models/operations/postgreschangestatusproject.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `projectId`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |