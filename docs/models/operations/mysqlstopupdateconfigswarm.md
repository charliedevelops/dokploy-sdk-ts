# MysqlStopUpdateConfigSwarm

## Example Usage

```typescript
import { MysqlStopUpdateConfigSwarm } from "dokploy-sdk/models/operations";

let value: MysqlStopUpdateConfigSwarm = {
  order: "<value>",
  parallelism: 6621.38,
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