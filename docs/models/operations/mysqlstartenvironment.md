# MysqlStartEnvironment

## Example Usage

```typescript
import { MysqlStartEnvironment } from "dokploy-sdk/models/operations";

let value: MysqlStartEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "psst parsnip phew huzzah",
  createdAt: "1714654761570",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: null,
    createdAt: "1717966087532",
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
| `project`                                                                    | [operations.MysqlStartProject](../../models/operations/mysqlstartproject.md) | :heavy_check_mark:                                                           | N/A                                                                          |