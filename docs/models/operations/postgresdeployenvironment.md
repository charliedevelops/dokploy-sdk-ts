# PostgresDeployEnvironment

## Example Usage

```typescript
import { PostgresDeployEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresDeployEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "publicity wretched sashay boo nervously aw safely including",
  createdAt: "1720627581902",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "patiently that in phew drat until great gripping regular nor",
    createdAt: "1735025392039",
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
| `project`                                                                            | [operations.PostgresDeployProject](../../models/operations/postgresdeployproject.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |