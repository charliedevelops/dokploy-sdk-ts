# RedisRemoveEnvironment

## Example Usage

```typescript
import { RedisRemoveEnvironment } from "dokploy-sdk/models/operations";

let value: RedisRemoveEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "secrecy eek reorient scheme",
  createdAt: "1732392792241",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "viciously elegantly supposing boastfully bah knight atop",
    createdAt: "1716559476779",
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
| `project`                                                                      | [operations.RedisRemoveProject](../../models/operations/redisremoveproject.md) | :heavy_check_mark:                                                             | N/A                                                                            |