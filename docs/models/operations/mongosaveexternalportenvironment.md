# MongoSaveExternalPortEnvironment

## Example Usage

```typescript
import { MongoSaveExternalPortEnvironment } from "dokploy-sdk/models/operations";

let value: MongoSaveExternalPortEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "despite overproduce except playfully",
  createdAt: "1713106398445",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "fisherman given till tattered",
    createdAt: "1711813881104",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `environmentId`                                                                                    | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `description`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `env`                                                                                              | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `projectId`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `project`                                                                                          | [operations.MongoSaveExternalPortProject](../../models/operations/mongosaveexternalportproject.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |