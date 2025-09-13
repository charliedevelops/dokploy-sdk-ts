# RedisChangeStatusEnvironment

## Example Usage

```typescript
import { RedisChangeStatusEnvironment } from "dokploy-sdk/models/operations";

let value: RedisChangeStatusEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: null,
  createdAt: "1725800351572",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "suspiciously whoever publicity",
    createdAt: "1722511417122",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `environmentId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `description`                                                                              | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `createdAt`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `env`                                                                                      | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `projectId`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `project`                                                                                  | [operations.RedisChangeStatusProject](../../models/operations/redischangestatusproject.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |