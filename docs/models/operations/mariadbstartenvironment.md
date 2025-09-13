# MariadbStartEnvironment

## Example Usage

```typescript
import { MariadbStartEnvironment } from "dokploy-sdk/models/operations";

let value: MariadbStartEnvironment = {
  createdAt: "1733042950020",
  description:
    "minus convection aside or carelessly gadzooks whoa helplessly obedient aboard",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1723904933546",
    description: "punctually gosh perfectly likewise pupil",
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
| `project`                                                                        | [operations.MariadbStartProject](../../models/operations/mariadbstartproject.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `projectId`                                                                      | *string*                                                                         | :heavy_check_mark:                                                               | N/A                                                                              |