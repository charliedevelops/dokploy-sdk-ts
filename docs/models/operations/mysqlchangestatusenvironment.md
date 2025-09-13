# MysqlChangeStatusEnvironment

## Example Usage

```typescript
import { MysqlChangeStatusEnvironment } from "dokploy-sdk/models/operations";

let value: MysqlChangeStatusEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "if whenever unrealistic ultimately anxiously pfft",
  createdAt: "1717633846782",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "but refine dampen violently casement for quarrel unlucky refine highly",
    createdAt: "1727451506644",
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
| `project`                                                                                  | [operations.MysqlChangeStatusProject](../../models/operations/mysqlchangestatusproject.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |