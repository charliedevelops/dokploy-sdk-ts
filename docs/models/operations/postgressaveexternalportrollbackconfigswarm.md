# PostgresSaveExternalPortRollbackConfigSwarm

## Example Usage

```typescript
import { PostgresSaveExternalPortRollbackConfigSwarm } from "dokploy-sdk/models/operations";

let value: PostgresSaveExternalPortRollbackConfigSwarm = {
  parallelism: 6890.99,
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