# MysqlStopEnvironment

## Example Usage

```typescript
import { MysqlStopEnvironment } from "dokploy-sdk/models/operations";

let value: MysqlStopEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "meal sizzling below reluctantly now",
  createdAt: "1705421589607",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "lawmaker since sandbar throughout however than excepting whenever although vanish",
    createdAt: "1710644887396",
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
| `project`                                                                  | [operations.MysqlStopProject](../../models/operations/mysqlstopproject.md) | :heavy_check_mark:                                                         | N/A                                                                        |