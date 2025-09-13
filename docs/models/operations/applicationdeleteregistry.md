# ApplicationDeleteRegistry

## Example Usage

```typescript
import { ApplicationDeleteRegistry } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteRegistry = {
  registryId: "<id>",
  registryName: "<value>",
  imagePrefix: "<value>",
  username: "Quentin.Lind",
  password: "h4GjA0drtQmWXNd",
  registryUrl: "https://creamy-summary.com",
  createdAt: "1710600280504",
  registryType: "cloud",
  organizationId: "<id>",
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `registryId`                                                                                         | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `registryName`                                                                                       | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `imagePrefix`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `username`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `password`                                                                                           | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `registryUrl`                                                                                        | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `createdAt`                                                                                          | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `registryType`                                                                                       | [operations.ApplicationDeleteRegistryType](../../models/operations/applicationdeleteregistrytype.md) | :heavy_check_mark:                                                                                   | N/A                                                                                                  |
| `organizationId`                                                                                     | *string*                                                                                             | :heavy_check_mark:                                                                                   | N/A                                                                                                  |