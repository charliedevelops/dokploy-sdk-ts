# MongoChangeStatusEnvironment

## Example Usage

```typescript
import { MongoChangeStatusEnvironment } from "dokploy-sdk/models/operations";

let value: MongoChangeStatusEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: null,
  createdAt: "1707576559835",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "furthermore drat hmph boulevard shear loudly relieve unlike",
    createdAt: "1721693165698",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `environmentId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `description`                                                                              | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `createdAt`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `env`                                                                                      | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `projectId`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `project`                                                                                  | [operations.MongoChangeStatusProject](../../models/operations/mongochangestatusproject.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |