# ProjectOneResponseBody

Successful response

## Example Usage

```typescript
import { ProjectOneResponseBody } from "dokploy-sdk/models/operations";

let value: ProjectOneResponseBody = {
  projectId: "<id>",
  name: "<value>",
  description: "to gastropod ouch accessorise",
  createdAt: "1735023197780",
  organizationId: "<id>",
  env: "<value>",
  environments: [],
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `projectId`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `name`                                                                                 | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `description`                                                                          | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `createdAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `organizationId`                                                                       | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `env`                                                                                  | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `environments`                                                                         | [operations.ProjectOneEnvironment](../../models/operations/projectoneenvironment.md)[] | :heavy_check_mark:                                                                     | N/A                                                                                    |