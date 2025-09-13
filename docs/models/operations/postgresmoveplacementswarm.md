# PostgresMovePlacementSwarm

## Example Usage

```typescript
import { PostgresMovePlacementSwarm } from "dokploy-sdk/models/operations";

let value: PostgresMovePlacementSwarm = {};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `constraints`                                                                            | *string*[]                                                                               | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `preferences`                                                                            | [operations.PostgresMovePreference](../../models/operations/postgresmovepreference.md)[] | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `maxReplicas`                                                                            | *number*                                                                                 | :heavy_minus_sign:                                                                       | N/A                                                                                      |
| `platforms`                                                                              | [operations.PostgresMovePlatform](../../models/operations/postgresmoveplatform.md)[]     | :heavy_minus_sign:                                                                       | N/A                                                                                      |