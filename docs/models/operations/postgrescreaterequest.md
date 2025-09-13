# PostgresCreateRequest

## Example Usage

```typescript
import { PostgresCreateRequest } from "dokploy-sdk/models/operations";

let value: PostgresCreateRequest = {
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  environmentId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `appName`          | *string*           | :heavy_check_mark: | N/A                |
| `databaseName`     | *string*           | :heavy_check_mark: | N/A                |
| `databaseUser`     | *string*           | :heavy_check_mark: | N/A                |
| `databasePassword` | *string*           | :heavy_check_mark: | N/A                |
| `dockerImage`      | *string*           | :heavy_minus_sign: | N/A                |
| `environmentId`    | *string*           | :heavy_check_mark: | N/A                |
| `description`      | *string*           | :heavy_minus_sign: | N/A                |
| `serverId`         | *string*           | :heavy_minus_sign: | N/A                |