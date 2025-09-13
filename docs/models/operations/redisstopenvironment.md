# RedisStopEnvironment

## Example Usage

```typescript
import { RedisStopEnvironment } from "dokploy-sdk/models/operations";

let value: RedisStopEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "soon spirit flash as of round around bah",
  createdAt: "1708664381982",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: null,
    createdAt: "1707226745819",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                      | Type                                                                       | Required                                                                   | Description                                                                |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| `environmentId`                                                            | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `name`                                                                     | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `description`                                                              | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `createdAt`                                                                | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `env`                                                                      | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `projectId`                                                                | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `project`                                                                  | [operations.RedisStopProject](../../models/operations/redisstopproject.md) | :heavy_check_mark:                                                         | N/A                                                                        |