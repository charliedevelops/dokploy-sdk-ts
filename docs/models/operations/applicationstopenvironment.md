# ApplicationStopEnvironment

## Example Usage

```typescript
import { ApplicationStopEnvironment } from "dokploy-sdk/models/operations";

let value: ApplicationStopEnvironment = {
  environmentId: "<id>",
  name: "<value>",
  description:
    "mentor phooey councilman before abaft bathhouse bank slather aha",
  createdAt: "1734994822806",
  env: "<value>",
  projectId: "<id>",
  project: {
    projectId: "<id>",
    name: "<value>",
    description:
      "overfeed valuable uh-huh bah why certainly reference yuck blah when",
    createdAt: "1735181652484",
    organizationId: "<id>",
    env: "<value>",
  },
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `environmentId`                                                                        | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `name`                                                                                 | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `description`                                                                          | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `createdAt`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `env`                                                                                  | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `projectId`                                                                            | *string*                                                                               | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `project`                                                                              | [operations.ApplicationStopProject](../../models/operations/applicationstopproject.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |