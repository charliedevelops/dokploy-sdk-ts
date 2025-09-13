# MongoStopEnvironment

## Example Usage

```typescript
import { MongoStopEnvironment } from "dokploy-sdk/models/operations";

let value: MongoStopEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: null,
  createdAt: "1735215791196",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "unwelcome hopelessly anneal",
    createdAt: "1725708514063",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                      | Type                                                                       | Required                                                                   | Description                                                                |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| `environmentId`                                                            | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `name`                                                                     | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `description`                                                              | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `createdAt`                                                                | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `env`                                                                      | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `projectId`                                                                | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `project`                                                                  | [operations.MongoStopProject](../../models/operations/mongostopproject.md) | :heavy_check_mark:                                                         | N/A                                                                        |