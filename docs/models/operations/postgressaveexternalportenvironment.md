# PostgresSaveExternalPortEnvironment

## Example Usage

```typescript
import { PostgresSaveExternalPortEnvironment } from "dokploy-sdk/models/operations";

let value: PostgresSaveExternalPortEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description:
    "nervously typeface editor ouch abaft boo entomb geez evenly while",
  createdAt: "1705294671079",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description: "clamour aw yahoo including makeover until since adult",
    createdAt: "1734472000190",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `environmentId`                                                                                          | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `name`                                                                                                   | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `description`                                                                                            | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `createdAt`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `env`                                                                                                    | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `projectId`                                                                                              | *string*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `project`                                                                                                | [operations.PostgresSaveExternalPortProject](../../models/operations/postgressaveexternalportproject.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |