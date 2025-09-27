# MongoStopEnvironment

## Example Usage

```typescript
import { MongoStopEnvironment } from "dokploy-sdk/models/operations";

let value: MongoStopEnvironment = {
  createdAt: "1705503692690",
  description:
    "unless huzzah below gee unlawful who collaboration bustling happy unbearably",
  env: "<value>",
  environmentId: "<id>",
  name: "<value>",
  project: {
    createdAt: "1718458472155",
    description: "guilt next pessimistic so surprisingly massage because",
    env: "<value>",
    name: "<value>",
    organizationId: "<id>",
    projectId: "<id>",
  },
  projectId: "<id>",
};
```

## Fields

| Field                                                                      | Type                                                                       | Required                                                                   | Description                                                                |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| `createdAt`                                                                | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `description`                                                              | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `env`                                                                      | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `environmentId`                                                            | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `name`                                                                     | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `project`                                                                  | [operations.MongoStopProject](../../models/operations/mongostopproject.md) | :heavy_check_mark:                                                         | N/A                                                                        |
| `projectId`                                                                | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |