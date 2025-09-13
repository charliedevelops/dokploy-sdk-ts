# RedisOneEnvironment

## Example Usage

```typescript
import { RedisOneEnvironment } from "dokploy-sdk/models/operations";

let value: RedisOneEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "modulo without while",
  createdAt: "1706089489212",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "descent huzzah hmph yak absentmindedly frantically made-up dependency",
    createdAt: "1715523153298",
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
| `project`                                                                | [operations.RedisOneProject](../../models/operations/redisoneproject.md) | :heavy_check_mark:                                                       | N/A                                                                      |