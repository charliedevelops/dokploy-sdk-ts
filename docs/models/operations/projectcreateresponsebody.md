# ProjectCreateResponseBody

Successful response

## Example Usage

```typescript
import { ProjectCreateResponseBody } from "dokploy-sdk/models/operations";

let value: ProjectCreateResponseBody = {
  environment: {
    createdAt: "1725570003304",
    description: "to golden cleverly huge against but yahoo",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    projectId: "<id>",
  },
  project: {
    createdAt: "1725339676238",
    description:
      "linseed against youthful polarisation but pike commonly yearningly given",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `environment`                                                                              | [operations.ProjectCreateEnvironment](../../models/operations/projectcreateenvironment.md) | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `project`                                                                                  | [operations.ProjectCreateProject](../../models/operations/projectcreateproject.md)         | :heavy_check_mark:                                                                         | N/A                                                                                        |