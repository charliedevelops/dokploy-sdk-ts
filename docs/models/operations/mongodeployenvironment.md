# MongoDeployEnvironment

## Example Usage

```typescript
import { MongoDeployEnvironment } from "dokploy-sdk/models/operations";

let value: MongoDeployEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "afterwards radiant unlike",
  createdAt: "1721569847705",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "by whereas queasily redress ick almighty blissfully",
    createdAt: "1727445144010",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `environmentId`                                                                | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `name`                                                                         | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `description`                                                                  | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `createdAt`                                                                    | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `env`                                                                          | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `projectId`                                                                    | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `project`                                                                      | [operations.MongoDeployProject](../../models/operations/mongodeployproject.md) | :heavy_check_mark:                                                             | N/A                                                                            |