# MongoMovePlacementSwarm

## Example Usage

```typescript
import { MongoMovePlacementSwarm } from "dokploy-sdk/models/operations";

let value: MongoMovePlacementSwarm = {};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `constraints`                                                                      | *string*[]                                                                         | :heavy_minus_sign:                                                                 | N/A                                                                                |
| `preferences`                                                                      | [operations.MongoMovePreference](../../models/operations/mongomovepreference.md)[] | :heavy_minus_sign:                                                                 | N/A                                                                                |
| `maxReplicas`                                                                      | *number*                                                                           | :heavy_minus_sign:                                                                 | N/A                                                                                |
| `platforms`                                                                        | [operations.MongoMovePlatform](../../models/operations/mongomoveplatform.md)[]     | :heavy_minus_sign:                                                                 | N/A                                                                                |