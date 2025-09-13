# MongoUpdatePlacementSwarm

## Example Usage

```typescript
import { MongoUpdatePlacementSwarm } from "dokploy-sdk/models/operations";

let value: MongoUpdatePlacementSwarm = {};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `constraints`                                                                          | *string*[]                                                                             | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `preferences`                                                                          | [operations.MongoUpdatePreference](../../models/operations/mongoupdatepreference.md)[] | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `maxReplicas`                                                                          | *number*                                                                               | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `platforms`                                                                            | [operations.MongoUpdatePlatform](../../models/operations/mongoupdateplatform.md)[]     | :heavy_minus_sign:                                                                     | N/A                                                                                    |