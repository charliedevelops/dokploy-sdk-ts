# PostgresStopEnvironment

## Example Usage

```typescript
import { PostgresStopEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresStopEnvironment = {
  createdAt: "1710322536134",
  description: "gadzooks usefully hmph ugh swat rebel sonnet",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1707969860361",
    description:
      "phooey bolster deer oof clone merrily ugh silky draw overplay",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
  projectId: "<id>",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `createdAt`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `description`                                                                    | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `env`                                                                            | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `environmentId`                                                                  | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `name`                                                                           | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `project`                                                                        | [operations.PostgresStopProject](../../models/operations/postgresstopproject.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `projectId`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |