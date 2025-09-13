# ComposeCreateRequest

## Example Usage

```typescript
import { ComposeCreateRequest } from "dokploy-sdk/models/operations";

let value: ComposeCreateRequest = {
  name: "<value>",
  environmentId: "<id>",
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `name`                                                                                     | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `description`                                                                              | *string*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `environmentId`                                                                            | *string*                                                                                   | :heavy_check_mark:                                                                         | N/A                                                                                        |
| `composeType`                                                                              | [operations.ComposeCreateComposeType](../../models/operations/composecreatecomposetype.md) | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `appName`                                                                                  | *string*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `serverId`                                                                                 | *string*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `composeFile`                                                                              | *string*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |