# MariadbStartEnvironment

## Example Usage

```typescript
import { MariadbStartEnvironment } from "dokploy-sdk/models/operations";

let value: MariadbStartEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description:
    "lest scale furthermore vet fervently abaft over fooey underpants birdbath",
  createdAt: "1704815948606",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "arbitrate supposing jovially solemnly out yuppify thankfully obligation",
    createdAt: "1713099423384",
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
| `project`                                                                        | [operations.MariadbStartProject](../../models/operations/mariadbstartproject.md) | :heavy_check_mark:                                                               | N/A                                                                              |