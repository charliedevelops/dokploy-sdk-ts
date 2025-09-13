# PostgresStartEnvironment

## Example Usage

```typescript
import { PostgresStartEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresStartEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "colour that carpool before passionate",
  createdAt: "1712276226605",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "general unless striking unless ick",
    createdAt: "1707999818079",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `environmentId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `name`                                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `description`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `env`                                                                              | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `projectId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `project`                                                                          | [operations.PostgresStartProject](../../models/operations/postgresstartproject.md) | :heavy_check_mark:                                                                 | N/A                                                                                |