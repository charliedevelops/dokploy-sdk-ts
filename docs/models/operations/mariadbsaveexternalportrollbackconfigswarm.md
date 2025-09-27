# MariadbSaveExternalPortRollbackConfigSwarm

## Example Usage

```typescript
import { MariadbSaveExternalPortRollbackConfigSwarm } from "dokploy-sdk/models/operations";

let value: MariadbSaveExternalPortRollbackConfigSwarm = {
  order: "<value>",
  parallelism: 1315.88,
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