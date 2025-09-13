# PostgresOnePlacementSwarm

## Example Usage

```typescript
import { PostgresOnePlacementSwarm } from "dokploy-sdk/models/operations";

let value: PostgresOnePlacementSwarm = {};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `constraints`                                                                          | *string*[]                                                                             | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `preferences`                                                                          | [operations.PostgresOnePreference](../../models/operations/postgresonepreference.md)[] | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `maxReplicas`                                                                          | *number*                                                                               | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `platforms`                                                                            | [operations.PostgresOnePlatform](../../models/operations/postgresoneplatform.md)[]     | :heavy_minus_sign:                                                                     | N/A                                                                                    |