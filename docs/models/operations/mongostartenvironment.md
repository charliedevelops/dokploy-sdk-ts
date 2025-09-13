# MongoStartEnvironment

## Example Usage

```typescript
import { MongoStartEnvironment } from "dokploy-sdk/models/operations";

let value: MongoStartEnvironment = {
  createdAt: "1719818705191",
  description:
    "amongst geez anenst giggle except community throughout tensely certainly whether",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1735427122788",
    description:
      "far-flung pish graduate begonia awful judicious leading pace upright",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
  projectId: "<id>",
};
```

## Fields

| Field                                                                        | Type                                                                         | Required                                                                     | Description                                                                  |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| `createdAt`                                                                  | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `description`                                                                | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `env`                                                                        | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `environmentId`                                                              | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `name`                                                                       | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |
| `project`                                                                    | [operations.MongoStartProject](../../models/operations/mongostartproject.md) | :heavy_check_mark:                                                           | N/A                                                                          |
| `projectId`                                                                  | *string*                                                                     | :heavy_check_mark:                                                           | N/A                                                                          |