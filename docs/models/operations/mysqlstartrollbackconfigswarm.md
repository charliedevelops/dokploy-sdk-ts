# MysqlStartRollbackConfigSwarm

## Example Usage

```typescript
import { MysqlStartRollbackConfigSwarm } from "dokploy-sdk/models/operations";

let value: MysqlStartRollbackConfigSwarm = {
  order: "<value>",
  parallelism: 5867.39,
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `delay`            | *number*           | :heavy_minus_sign: | N/A                |
| `failureAction`    | *string*           | :heavy_minus_sign: | N/A                |
| `maxFailureRatio`  | *number*           | :heavy_minus_sign: | N/A                |
| `monitor`          | *number*           | :heavy_minus_sign: | N/A                |
| `order`            | *string*           | :heavy_check_mark: | N/A                |
| `parallelism`      | *number*           | :heavy_check_mark: | N/A                |