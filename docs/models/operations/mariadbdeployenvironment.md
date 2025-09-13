# MariadbDeployEnvironment

## Example Usage

```typescript
import { MariadbDeployEnvironment } from "dokploy-sdk/models/operations";

let value: MariadbDeployEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "diligent below so pertain tinted",
  createdAt: "1712674198829",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "deduct guzzle while homely up optimistically instead huzzah",
    createdAt: "1723177725048",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `environmentId`                                                                    | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `name`                                                                             | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `description`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `createdAt`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `env`                                                                              | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `projectId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `project`                                                                          | [operations.MariadbDeployProject](../../models/operations/mariadbdeployproject.md) | :heavy_check_mark:                                                                 | N/A                                                                                |