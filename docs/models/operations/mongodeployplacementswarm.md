# MongoDeployPlacementSwarm

## Example Usage

```typescript
import { MongoDeployPlacementSwarm } from "dokploy-sdk/models/operations";

let value: MongoDeployPlacementSwarm = {};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `constraints`                                                                          | *string*[]                                                                             | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `maxReplicas`                                                                          | *number*                                                                               | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `platforms`                                                                            | [operations.MongoDeployPlatform](../../models/operations/mongodeployplatform.md)[]     | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `preferences`                                                                          | [operations.MongoDeployPreference](../../models/operations/mongodeploypreference.md)[] | :heavy_minus_sign:                                                                     | N/A                                                                                    |