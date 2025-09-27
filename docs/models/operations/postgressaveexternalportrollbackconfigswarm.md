# PostgresSaveExternalPortRollbackConfigSwarm

## Example Usage

```typescript
import { PostgresSaveExternalPortRollbackConfigSwarm } from "dokploy-sdk/models/operations";

let value: PostgresSaveExternalPortRollbackConfigSwarm = {
  order: "<value>",
  parallelism: 6890.99,
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