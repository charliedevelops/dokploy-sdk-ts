# ApplicationStartRegistry

## Example Usage

```typescript
import { ApplicationStartRegistry } from "dokploy-sdk/models/operations";

let value: ApplicationStartRegistry = {
  registryId: "<id>",
  registryName: "<value>",
  imagePrefix: null,
  username: "Rosella_Cruickshank",
  password: "Jezzow4TRZl86eW",
  registryUrl: "https://fragrant-loaf.net/",
  createdAt: "1717230841411",
  registryType: "selfHosted",
  organizationId: "<id>",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `registryId`                                                                                       | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `registryName`                                                                                     | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `imagePrefix`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `username`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `password`                                                                                         | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `registryUrl`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `registryType`                                                                                     | [operations.ApplicationStartRegistryType](../../models/operations/applicationstartregistrytype.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `organizationId`                                                                                   | *string*                                                                                           | :heavy_check_mark:                                                                                 | N/A                                                                                                |