# MariadbOneEnvironment

## Example Usage

```typescript
import { MariadbOneEnvironment } from "dokploy-sdk/models/operations";

let value: MariadbOneEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "ha regulate reassuringly and than lavish inconsequential",
  createdAt: "1722986480036",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "boohoo meh so round lumpy nor unimportant",
    createdAt: "1725568589968",
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
| `project`                                                                    | [operations.MariadbOneProject](../../models/operations/mariadboneproject.md) | :heavy_check_mark:                                                           | N/A                                                                          |