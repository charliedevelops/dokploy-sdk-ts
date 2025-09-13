# RegistryCreateRequest

## Example Usage

```typescript
import { RegistryCreateRequest } from "dokploy-sdk/models/operations";

let value: RegistryCreateRequest = {
  registryName: "<value>",
  username: "Charity53",
  password: "xJ6g0XxPPsq6BwW",
  registryUrl: "https://joyful-toothpick.com/",
  registryType: "cloud",
  imagePrefix: "<value>",
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `registryName`                                                                                 | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `username`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `password`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `registryUrl`                                                                                  | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `registryType`                                                                                 | [operations.RegistryCreateRegistryType](../../models/operations/registrycreateregistrytype.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `imagePrefix`                                                                                  | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serverId`                                                                                     | *string*                                                                                       | :heavy_minus_sign:                                                                             | N/A                                                                                            |