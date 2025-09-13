# ApplicationOneEnvironment

## Example Usage

```typescript
import { ApplicationOneEnvironment } from "dokploy-sdk/models/operations";

let value: ApplicationOneEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "peninsula yowza onto wherever besides",
  createdAt: "1720993832828",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "bulky including expatiate train realistic physically coexist beyond greatly hmph",
    createdAt: "1734678614871",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `environmentId`                                                                      | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `name`                                                                               | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `description`                                                                        | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `createdAt`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `env`                                                                                | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `projectId`                                                                          | *string*                                                                             | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `project`                                                                            | [operations.ApplicationOneProject](../../models/operations/applicationoneproject.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |