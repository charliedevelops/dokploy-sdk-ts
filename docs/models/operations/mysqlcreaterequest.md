# MysqlCreateRequest

## Example Usage

```typescript
import { MysqlCreateRequest } from "dokploy-sdk/models/operations";

let value: MysqlCreateRequest = {
  name: "<value>",
  appName: "<value>",
  environmentId: "<id>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
};
```

## Fields

| Field                  | Type                   | Required               | Description            |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| `name`                 | *string*               | :heavy_check_mark:     | N/A                    |
| `appName`              | *string*               | :heavy_check_mark:     | N/A                    |
| `dockerImage`          | *string*               | :heavy_minus_sign:     | N/A                    |
| `environmentId`        | *string*               | :heavy_check_mark:     | N/A                    |
| `description`          | *string*               | :heavy_minus_sign:     | N/A                    |
| `databaseName`         | *string*               | :heavy_check_mark:     | N/A                    |
| `databaseUser`         | *string*               | :heavy_check_mark:     | N/A                    |
| `databasePassword`     | *string*               | :heavy_check_mark:     | N/A                    |
| `databaseRootPassword` | *string*               | :heavy_check_mark:     | N/A                    |
| `serverId`             | *string*               | :heavy_minus_sign:     | N/A                    |