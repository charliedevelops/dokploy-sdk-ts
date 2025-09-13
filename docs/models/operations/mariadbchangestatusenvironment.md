# MariadbChangeStatusEnvironment

## Example Usage

```typescript
import { MariadbChangeStatusEnvironment } from "dokploy-sdk/models/operations";

let value: MariadbChangeStatusEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "hypothesize ribbon for giving mortar stable",
  createdAt: "1704683550312",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "councilman language frightfully pish aha perfectly fearless whether",
    createdAt: "1719623363118",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `environmentId`                                                                                | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `name`                                                                                         | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `description`                                                                                  | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `createdAt`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `env`                                                                                          | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `projectId`                                                                                    | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `project`                                                                                      | [operations.MariadbChangeStatusProject](../../models/operations/mariadbchangestatusproject.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |