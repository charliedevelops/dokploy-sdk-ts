# RedisSaveExternalPortEnvironment

## Example Usage

```typescript
import { RedisSaveExternalPortEnvironment } from "dokploy-sdk/models/operations";

let value: RedisSaveExternalPortEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: null,
  createdAt: "1704891391998",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "weird via hence hence",
    createdAt: "1734882822266",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `environmentId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `env`                                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `projectId`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `project`                                                                                          | [operations.RedisSaveExternalPortProject](../../models/operations/redissaveexternalportproject.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |