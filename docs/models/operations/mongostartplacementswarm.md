# MongoStartPlacementSwarm

## Example Usage

```typescript
import { MongoStartPlacementSwarm } from "dokploy-sdk/models/operations";

let value: MongoStartPlacementSwarm = {};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `constraints`                                                                        | *string*[]                                                                           | :heavy_minus_sign:                                                                   | N/A                                                                                  |
| `preferences`                                                                        | [operations.MongoStartPreference](../../models/operations/mongostartpreference.md)[] | :heavy_minus_sign:                                                                   | N/A                                                                                  |
| `maxReplicas`                                                                        | *number*                                                                             | :heavy_minus_sign:                                                                   | N/A                                                                                  |
| `platforms`                                                                          | [operations.MongoStartPlatform](../../models/operations/mongostartplatform.md)[]     | :heavy_minus_sign:                                                                   | N/A                                                                                  |