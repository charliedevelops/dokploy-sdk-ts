# PostgresRemoveEnvironment

## Example Usage

```typescript
import { PostgresRemoveEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresRemoveEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "till wordy though",
  createdAt: "1707665466735",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: null,
    createdAt: "1730231254737",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `environmentId`                                                                      | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `description`                                                                        | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `env`                                                                                | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `projectId`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `project`                                                                            | [operations.PostgresRemoveProject](../../models/operations/postgresremoveproject.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |