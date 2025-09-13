# MongoOneEnvironment

## Example Usage

```typescript
import { MongoOneEnvironment } from "dokploy-sdk/models/operations";

let value: MongoOneEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "powerful smart below circumnavigate",
  createdAt: "1708947035692",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "smoke accredit shred incidentally how guzzle",
    createdAt: "1709765042867",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                    | Type                                                                     | Required                                                                 | Description                                                              |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| `environmentId`                                                          | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `name`                                                                   | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `description`                                                            | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `createdAt`                                                              | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `env`                                                                    | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `projectId`                                                              | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `project`                                                                | [operations.MongoOneProject](../../models/operations/mongooneproject.md) | :heavy_check_mark:                                                       | N/A                                                                      |