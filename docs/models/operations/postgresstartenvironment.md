# PostgresStartEnvironment

## Example Usage

```typescript
import { PostgresStartEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresStartEnvironment = {
  createdAt: "1712596390135",
  description: "thoroughly inveigle moisten",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1713960768591",
    description: "worth showboat soliloquy proselytise",
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
| `project`                                                                          | [operations.PostgresStartProject](../../models/operations/postgresstartproject.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `projectId`                                                                        | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |