# MariadbOneRollbackConfigSwarm

## Example Usage

```typescript
import { MariadbOneRollbackConfigSwarm } from "dokploy-sdk/models/operations";

let value: MariadbOneRollbackConfigSwarm = {
  order: "<value>",
  parallelism: 5837.29,
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