# MariadbRemoveEnvironment

## Example Usage

```typescript
import { MariadbRemoveEnvironment } from "dokploy-sdk/models/operations";

let value: MariadbRemoveEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "exalted thoroughly pinion elegantly justly",
  createdAt: "1724777424069",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "spook whenever soup airbus zealous for deduct amid",
    createdAt: "1712617458655",
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
| `project`                                                                          | [operations.MariadbRemoveProject](../../models/operations/mariadbremoveproject.md) | :heavy_check_mark:                                                                 | N/A                                                                                |