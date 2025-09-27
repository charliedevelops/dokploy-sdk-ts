# MongoOneEnvironment

## Example Usage

```typescript
import { MongoOneEnvironment } from "dokploy-sdk/models/operations";

let value: MongoOneEnvironment = {
  createdAt: "1711888385065",
  description:
    "jagged complicated duster consequently eek in thorn yuck knowingly gentle",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1715567682812",
    description: "sticker uh-huh drag habit",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
  projectId: "<id>",
};
```

## Fields

| Field                                                                    | Type                                                                     | Required                                                                 | Description                                                              |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| `createdAt`                                                              | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `description`                                                            | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `env`                                                                    | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `environmentId`                                                          | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `name`                                                                   | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `project`                                                                | [operations.MongoOneProject](../../models/operations/mongooneproject.md) | :heavy_check_mark:                                                       | N/A                                                                      |
| `projectId`                                                              | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |