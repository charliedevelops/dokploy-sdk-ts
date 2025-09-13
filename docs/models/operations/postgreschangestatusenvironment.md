# PostgresChangeStatusEnvironment

## Example Usage

```typescript
import { PostgresChangeStatusEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresChangeStatusEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "scrutinise to circa abaft frightfully neaten obedient",
  createdAt: "1730308973947",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "crushing colorfully regulate",
    createdAt: "1704457250165",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `environmentId`                                                                                  | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `description`                                                                                    | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `createdAt`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `env`                                                                                            | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `projectId`                                                                                      | *string*                                                                                         | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `project`                                                                                        | [operations.PostgresChangeStatusProject](../../models/operations/postgreschangestatusproject.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |