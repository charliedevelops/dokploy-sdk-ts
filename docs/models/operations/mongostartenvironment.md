# MongoStartEnvironment

## Example Usage

```typescript
import { MongoStartEnvironment } from "dokploy-sdk/models/operations";

let value: MongoStartEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "consequently provided or scramble ouch",
  createdAt: "1717268387893",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "whereas whirlwind vainly which turret probe whoever near hello",
    createdAt: "1706362761378",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                        | Type                                                                         | Required                                                                     | Description                                                                  |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| `environmentId`                                                              | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `name`                                                                       | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `description`                                                                | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `createdAt`                                                                  | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `env`                                                                        | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `projectId`                                                                  | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `project`                                                                    | [operations.MongoStartProject](../../models/operations/mongostartproject.md) | :heavy_check_mark:                                                           | N/A                                                                          |