# ApplicationDeleteEnvironment

## Example Usage

```typescript
import { ApplicationDeleteEnvironment } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description: "beep fictionalize riser amid joyfully",
  createdAt: "1706939328672",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "er opposite loyally following thyme reservation abaft for feline",
    createdAt: "1718849910278",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `environmentId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `description`                                                                              | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `createdAt`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `env`                                                                                      | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `projectId`                                                                                | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `project`                                                                                  | [operations.ApplicationDeleteProject](../../models/operations/applicationdeleteproject.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |