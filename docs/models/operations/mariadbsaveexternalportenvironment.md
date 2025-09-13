# MariadbSaveExternalPortEnvironment

## Example Usage

```typescript
import { MariadbSaveExternalPortEnvironment } from "dokploy-sdk/models/operations";

let value: MariadbSaveExternalPortEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "huzzah pace ostrich than",
  createdAt: "1705698420710",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "assail although er",
    createdAt: "1723720328670",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `environmentId`                                                                                        | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `name`                                                                                                 | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `description`                                                                                          | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `createdAt`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `env`                                                                                                  | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `projectId`                                                                                            | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `project`                                                                                              | [operations.MariadbSaveExternalPortProject](../../models/operations/mariadbsaveexternalportproject.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |