# MariadbDeployEnvironment

## Example Usage

```typescript
import { MariadbDeployEnvironment } from "dokploy-sdk/models/operations";

let value: MariadbDeployEnvironment = {
  createdAt: "1727712651927",
  description: "beneath dilate since epic finished ah up foolishly fledgling",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1726195672478",
    description: "hello institutionalize browse",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
  projectId: "<id>",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `description`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `env`                                                                              | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `environmentId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `name`                                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `project`                                                                          | [operations.MariadbDeployProject](../../models/operations/mariadbdeployproject.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `projectId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |