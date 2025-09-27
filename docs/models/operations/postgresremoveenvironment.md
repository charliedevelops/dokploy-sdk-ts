# PostgresRemoveEnvironment

## Example Usage

```typescript
import { PostgresRemoveEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresRemoveEnvironment = {
  createdAt: "1710100775121",
  description: null,
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1722918008081",
    description: "sanity beyond slink purse euphonium",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
  projectId: "<id>",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `description`                                                                        | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `env`                                                                                | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `environmentId`                                                                      | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `project`                                                                            | [operations.PostgresRemoveProject](../../models/operations/postgresremoveproject.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `projectId`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |