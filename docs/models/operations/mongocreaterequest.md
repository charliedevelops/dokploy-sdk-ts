# MongoCreateRequest

## Example Usage

```typescript
import { MongoCreateRequest } from "dokploy-sdk/models/operations";

let value: MongoCreateRequest = {
  appName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  environmentId: "<id>",
  name: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `appName`          | *string*           | :heavy_check_mark: | N/A                |
| `databasePassword` | *string*           | :heavy_check_mark: | N/A                |
| `databaseUser`     | *string*           | :heavy_check_mark: | N/A                |
| `description`      | *string*           | :heavy_minus_sign: | N/A                |
| `dockerImage`      | *string*           | :heavy_minus_sign: | N/A                |
| `environmentId`    | *string*           | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `replicaSets`      | *boolean*          | :heavy_minus_sign: | N/A                |
| `serverId`         | *string*           | :heavy_minus_sign: | N/A                |