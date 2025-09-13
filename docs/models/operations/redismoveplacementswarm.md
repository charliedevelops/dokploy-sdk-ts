# RedisMovePlacementSwarm

## Example Usage

```typescript
import { RedisMovePlacementSwarm } from "dokploy-sdk/models/operations";

let value: RedisMovePlacementSwarm = {};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `constraints`                                                                      | *string*[]                                                                         | :heavy_minus_sign:                                                                 | N/A                                                                                |
| `preferences`                                                                      | [operations.RedisMovePreference](../../models/operations/redismovepreference.md)[] | :heavy_minus_sign:                                                                 | N/A                                                                                |
| `maxReplicas`                                                                      | *number*                                                                           | :heavy_minus_sign:                                                                 | N/A                                                                                |
| `platforms`                                                                        | [operations.RedisMovePlatform](../../models/operations/redismoveplatform.md)[]     | :heavy_minus_sign:                                                                 | N/A                                                                                |