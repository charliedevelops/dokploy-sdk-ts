# MariadbDeployPlacementSwarm

## Example Usage

```typescript
import { MariadbDeployPlacementSwarm } from "dokploy-sdk/models/operations";

let value: MariadbDeployPlacementSwarm = {};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `constraints`                                                                              | *string*[]                                                                                 | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `maxReplicas`                                                                              | *number*                                                                                   | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `platforms`                                                                                | [operations.MariadbDeployPlatform](../../models/operations/mariadbdeployplatform.md)[]     | :heavy_minus_sign:                                                                         | N/A                                                                                        |
| `preferences`                                                                              | [operations.MariadbDeployPreference](../../models/operations/mariadbdeploypreference.md)[] | :heavy_minus_sign:                                                                         | N/A                                                                                        |