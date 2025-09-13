# MysqlRemoveEnvironment

## Example Usage

```typescript
import { MysqlRemoveEnvironment } from "dokploy-sdk/models/operations";

let value: MysqlRemoveEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "bustling sour considering boohoo rough sunbeam",
  createdAt: "1724110176885",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "hmph hence than officially so border furthermore so phew obedience",
    createdAt: "1706704360529",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `environmentId`                                                                | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `name`                                                                         | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `description`                                                                  | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `createdAt`                                                                    | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `env`                                                                          | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `projectId`                                                                    | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `project`                                                                      | [operations.MysqlRemoveProject](../../models/operations/mysqlremoveproject.md) | :heavy_check_mark:                                                             | N/A                                                                            |