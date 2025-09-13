# ProjectCreateResponseBody

Successful response

## Example Usage

```typescript
import { ProjectCreateResponseBody } from "dokploy-sdk/models/operations";

let value: ProjectCreateResponseBody = {
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "inexperienced radiant beyond own from tomorrow supposing shrilly",
    createdAt: "1709399862185",
    organizationId: "<id>",
    env: "<value>",
  },
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "dividend recede opposite perfectly fiercely fatal gray equally concerning",
    createdAt: "1712583993211",
    env: "<value>",
    projectId: "<id>",
  },
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `project`                                                                                  | [operations.ProjectCreateProject](../../models/operations/projectcreateproject.md)         | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `environment`                                                                              | [operations.ProjectCreateEnvironment](../../models/operations/projectcreateenvironment.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |