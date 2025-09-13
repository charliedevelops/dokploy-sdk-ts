# PostgresOneEnvironment

## Example Usage

```typescript
import { PostgresOneEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresOneEnvironment = {
  createdAt: "1706616268371",
  description: "broadly oof duh juvenile below",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1705027263361",
    description: "softly for than who aw",
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
| `project`                                                                      | [operations.PostgresOneProject](../../models/operations/postgresoneproject.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `projectId`                                                                    | *string*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |