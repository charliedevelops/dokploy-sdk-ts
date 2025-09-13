# RedisStartEnvironment

## Example Usage

```typescript
import { RedisStartEnvironment } from "dokploy-sdk/models/operations";

let value: RedisStartEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "slipper whereas at far hmph think linear",
  createdAt: "1711237187184",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "oil wisely on who",
    createdAt: "1734550191951",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                        | Type                                                                         | Required                                                                     | Description                                                                  |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| `environmentId`                                                              | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `name`                                                                       | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `description`                                                                | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `createdAt`                                                                  | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `env`                                                                        | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `projectId`                                                                  | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `project`                                                                    | [operations.RedisStartProject](../../models/operations/redisstartproject.md) | :heavy_check_mark:                                                           | N/A                                                                          |