# ProjectDuplicateRequest

## Example Usage

```typescript
import { ProjectDuplicateRequest } from "dokploy-sdk/models/operations";

let value: ProjectDuplicateRequest = {
  sourceEnvironmentId: "<id>",
  name: "<value>",
};
```

## Fields

| Field                                                                      | Type                                                                       | Required                                                                   | Description                                                                |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| `sourceEnvironmentId`                                                      | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `name`                                                                     | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `description`                                                              | *string*                                                                   | :heavy_minus_sign:                                                         | N/A                                                                        |
| `includeServices`                                                          | *boolean*                                                                  | :heavy_minus_sign:                                                         | N/A                                                                        |
| `selectedServices`                                                         | [operations.SelectedService](../../models/operations/selectedservice.md)[] | :heavy_minus_sign:                                                         | N/A                                                                        |
| `duplicateInSameProject`                                                   | *boolean*                                                                  | :heavy_minus_sign:                                                         | N/A                                                                        |