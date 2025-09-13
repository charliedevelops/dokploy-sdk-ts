# PostgresStartPlacementSwarm

## Example Usage

```typescript
import { PostgresStartPlacementSwarm } from "dokploy-sdk/models/operations";

let value: PostgresStartPlacementSwarm = {};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `constraints`                                                                              | *string*[]                                                                                 | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `maxReplicas`                                                                              | *number*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `platforms`                                                                                | [operations.PostgresStartPlatform](../../models/operations/postgresstartplatform.md)[]     | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `preferences`                                                                              | [operations.PostgresStartPreference](../../models/operations/postgresstartpreference.md)[] | :heavy_minus_sign:                                                                         | N/A                                                                                        |