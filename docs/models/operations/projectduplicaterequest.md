# ProjectDuplicateRequest

## Example Usage

```typescript
import { ProjectDuplicateRequest } from "dokploy-sdk/models/operations";

let value: ProjectDuplicateRequest = {
  name: "<value>",
  sourceEnvironmentId: "<id>",
};
```

## Fields

| Field                                                                      | Type                                                                       | Required                                                                   | Description                                                                |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| `description`                                                              | *string*                                                                   | :heavy_minus_sign:                                                         | N/A                                                                        |
| `duplicateInSameProject`                                                   | *boolean*                                                                  | :heavy_minus_sign:                                                         | N/A                                                                        |
| `includeServices`                                                          | *boolean*                                                                  | :heavy_minus_sign:                                                         | N/A                                                                        |
| `name`                                                                     | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |
| `selectedServices`                                                         | [operations.SelectedService](../../models/operations/selectedservice.md)[] | :heavy_minus_sign:                                                         | N/A                                                                        |
| `sourceEnvironmentId`                                                      | *string*                                                                   | :heavy_check_mark:                                                         | N/A                                                                        |