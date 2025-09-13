# RedisStartPlacementSwarm

## Example Usage

```typescript
import { RedisStartPlacementSwarm } from "dokploy-sdk/models/operations";

let value: RedisStartPlacementSwarm = {};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `constraints`                                                                        | *string*[]                                                                           | :heavy_minus_sign:                                                                   | N/A                                                                                  |
| `preferences`                                                                        | [operations.RedisStartPreference](../../models/operations/redisstartpreference.md)[] | :heavy_minus_sign:                                                                   | N/A                                                                                  |
| `maxReplicas`                                                                        | *number*                                                                             | :heavy_minus_sign:                                                                   | N/A                                                                                  |
| `platforms`                                                                          | [operations.RedisStartPlatform](../../models/operations/redisstartplatform.md)[]     | :heavy_minus_sign:                                                                   | N/A                                                                                  |