# RedisRemoveEnvironment

## Example Usage

```typescript
import { RedisRemoveEnvironment } from "dokploy-sdk/models/operations";

let value: RedisRemoveEnvironment = {
  createdAt: "1711614609691",
  description:
    "gadzooks apricot quick unlike willing tensely now even but cone",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1709314426668",
    description: "aha versus verbally oh augment whether",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
  projectId: "<id>",
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `createdAt`                                                                    | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `description`                                                                  | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `env`                                                                          | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `environmentId`                                                                | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `name`                                                                         | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `project`                                                                      | [operations.RedisRemoveProject](../../models/operations/redisremoveproject.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `projectId`                                                                    | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |