# MongoCreateRequest

## Example Usage

```typescript
import { MongoCreateRequest } from "dokploy-sdk/models/operations";

let value: MongoCreateRequest = {
  name: "<value>",
  appName: "<value>",
  environmentId: "<id>",
  databaseUser: "<value>",
  databasePassword: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `appName`          | *string*           | :heavy_check_mark: | N/A                |
| `dockerImage`      | *string*           | :heavy_minus_sign: | N/A                |
| `environmentId`    | *string*           | :heavy_check_mark: | N/A                |
| `description`      | *string*           | :heavy_minus_sign: | N/A                |
| `databaseUser`     | *string*           | :heavy_check_mark: | N/A                |
| `databasePassword` | *string*           | :heavy_check_mark: | N/A                |
| `serverId`         | *string*           | :heavy_minus_sign: | N/A                |
| `replicaSets`      | *boolean*          | :heavy_minus_sign: | N/A                |