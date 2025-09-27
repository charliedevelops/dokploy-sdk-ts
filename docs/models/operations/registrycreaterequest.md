# RegistryCreateRequest

## Example Usage

```typescript
import { RegistryCreateRequest } from "dokploy-sdk/models/operations";

let value: RegistryCreateRequest = {
  imagePrefix: "<value>",
  password: "6CSixJ6g0XxPPsq",
  registryName: "<value>",
  registryType: "cloud",
  registryUrl: "https://guilty-tinderbox.name/",
  username: "Dillan27",
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `imagePrefix`                                                                                  | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `password`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `registryName`                                                                                 | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `registryType`                                                                                 | [operations.RegistryCreateRegistryType](../../models/operations/registrycreateregistrytype.md) | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `registryUrl`                                                                                  | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |
| `serverId`                                                                                     | *string*                                                                                       | :heavy_minus_sign:                                                                             | N/A                                                                                            |
| `username`                                                                                     | *string*                                                                                       | :heavy_check_mark:                                                                             | N/A                                                                                            |