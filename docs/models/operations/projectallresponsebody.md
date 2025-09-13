# ProjectAllResponseBody

## Example Usage

```typescript
import { ProjectAllResponseBody } from "dokploy-sdk/models/operations";

let value: ProjectAllResponseBody = {
  projectId: "<id>",
  name: "<value>",
  description: "pointed ew mechanically but",
  createdAt: "1722992486431",
  organizationId: "<id>",
  env: "<value>",
  environments: [
    {
      environmentId: "<id>",
      name: "<value>",
      description: "windy unimpressively destock",
      createdAt: "1723524699574",
      env: "<value>",
      projectId: "<id>",
    },
  ],
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
| `environments`                                                                         | [operations.ProjectAllEnvironment](../../models/operations/projectallenvironment.md)[] | :heavy_check_mark:                                                                     | N/A                                                                                    |