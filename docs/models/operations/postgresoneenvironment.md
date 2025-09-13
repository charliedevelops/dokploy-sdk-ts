# PostgresOneEnvironment

## Example Usage

```typescript
import { PostgresOneEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresOneEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: null,
  createdAt: "1718283233305",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "fully yearly fooey usefully oh phew above",
    createdAt: "1729177506214",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `environmentId`                                                                | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `name`                                                                         | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `description`                                                                  | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `createdAt`                                                                    | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `env`                                                                          | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `projectId`                                                                    | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `project`                                                                      | [operations.PostgresOneProject](../../models/operations/postgresoneproject.md) | :heavy_check_mark:                                                             | N/A                                                                            |