# MysqlDeployEnvironment

## Example Usage

```typescript
import { MysqlDeployEnvironment } from "dokploy-sdk/models/operations";

let value: MysqlDeployEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "weatherize reasoning noisily like testimonial carefully yum",
  createdAt: "1729478170833",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: null,
    createdAt: "1729299618308",
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
| `project`                                                                      | [operations.MysqlDeployProject](../../models/operations/mysqldeployproject.md) | :heavy_check_mark:                                                             | N/A                                                                            |