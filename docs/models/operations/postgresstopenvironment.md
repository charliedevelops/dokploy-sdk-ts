# PostgresStopEnvironment

## Example Usage

```typescript
import { PostgresStopEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresStopEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description:
    "alongside confute authentic quaintly regarding zowie stoop bend than",
  createdAt: "1728618441856",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "duh so now alongside",
    createdAt: "1719356730252",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `environmentId`                                                                  | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `name`                                                                           | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `description`                                                                    | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `createdAt`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `env`                                                                            | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `projectId`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |
| `project`                                                                        | [operations.PostgresStopProject](../../models/operations/postgresstopproject.md) | :heavy_check_mark:                                                               | N/A                                                                              |