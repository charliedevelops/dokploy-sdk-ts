# RedisDeployEnvironment

## Example Usage

```typescript
import { RedisDeployEnvironment } from "dokploy-sdk/models/operations";

let value: RedisDeployEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "notarize unabashedly gratefully",
  createdAt: "1729215781182",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: null,
    createdAt: "1732134708142",
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
| `project`                                                                      | [operations.RedisDeployProject](../../models/operations/redisdeployproject.md) | :heavy_check_mark:                                                             | N/A                                                                            |