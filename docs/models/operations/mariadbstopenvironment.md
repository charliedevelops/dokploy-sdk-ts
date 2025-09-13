# MariadbStopEnvironment

## Example Usage

```typescript
import { MariadbStopEnvironment } from "dokploy-sdk/models/operations";

let value: MariadbStopEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "edible knottily after aha nervously blah scoff",
  createdAt: "1724466351329",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "elver mmm potable geez instead ugh snoop",
    createdAt: "1726446634911",
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
| `project`                                                                      | [operations.MariadbStopProject](../../models/operations/mariadbstopproject.md) | :heavy_check_mark:                                                             | N/A                                                                            |