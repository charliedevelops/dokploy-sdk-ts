# RedisOneEnvironment

## Example Usage

```typescript
import { RedisOneEnvironment } from "dokploy-sdk/models/operations";

let value: RedisOneEnvironment = {
  createdAt: "1719586934385",
  description: "glisten juvenile beloved but or whenever",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1706582335848",
    description: "until shakily inasmuch",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
  projectId: "<id>",
};
```

## Fields

| Field                                                                    | Type                                                                     | Required                                                                 | Description                                                              |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| `createdAt`                                                              | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `description`                                                            | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `env`                                                                    | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `environmentId`                                                          | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `name`                                                                   | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `project`                                                                | [operations.RedisOneProject](../../models/operations/redisoneproject.md) | :heavy_check_mark:                                                       | N/A                                                                      |
| `projectId`                                                              | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |