# RedisDeployPlacementSwarm

## Example Usage

```typescript
import { RedisDeployPlacementSwarm } from "dokploy-sdk/models/operations";

let value: RedisDeployPlacementSwarm = {};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `constraints`                                                                          | *string*[]                                                                             | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `preferences`                                                                          | [operations.RedisDeployPreference](../../models/operations/redisdeploypreference.md)[] | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `maxReplicas`                                                                          | *number*                                                                               | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `platforms`                                                                            | [operations.RedisDeployPlatform](../../models/operations/redisdeployplatform.md)[]     | :heavy_minus_sign:                                                                     | N/A                                                                                    |