# RedisDeployRollbackConfigSwarm

## Example Usage

```typescript
import { RedisDeployRollbackConfigSwarm } from "dokploy-sdk/models/operations";

let value: RedisDeployRollbackConfigSwarm = {
  parallelism: 9667.73,
  order: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `parallelism`      | *number*           | :heavy_check_mark: | N/A                |
| `delay`            | *number*           | :heavy_minus_sign: | N/A                |
| `failureAction`    | *string*           | :heavy_minus_sign: | N/A                |
| `monitor`          | *number*           | :heavy_minus_sign: | N/A                |
| `maxFailureRatio`  | *number*           | :heavy_minus_sign: | N/A                |
| `order`            | *string*           | :heavy_check_mark: | N/A                |