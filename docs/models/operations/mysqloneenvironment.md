# MysqlOneEnvironment

## Example Usage

```typescript
import { MysqlOneEnvironment } from "dokploy-sdk/models/operations";

let value: MysqlOneEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "given subexpression eek sticky",
  createdAt: "1719375910294",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "hourly how lecture quixotic hole drive as scale what but",
    createdAt: "1732002276444",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                    | Type                                                                     | Required                                                                 | Description                                                              |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| `environmentId`                                                          | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `name`                                                                   | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `description`                                                            | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `createdAt`                                                              | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `env`                                                                    | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `projectId`                                                              | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `project`                                                                | [operations.MysqlOneProject](../../models/operations/mysqloneproject.md) | :heavy_check_mark:                                                       | N/A                                                                      |