# ApplicationStartEnvironment

## Example Usage

```typescript
import { ApplicationStartEnvironment } from "dokploy-sdk/models/operations";

let value: ApplicationStartEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "even unto above hence private",
  createdAt: "1714053634673",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "tankful yahoo hence neck",
    createdAt: "1709110549258",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `environmentId`                                                                          | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `name`                                                                                   | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `description`                                                                            | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `createdAt`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `env`                                                                                    | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `projectId`                                                                              | *string*                                                                                 | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `project`                                                                                | [operations.ApplicationStartProject](../../models/operations/applicationstartproject.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |