# PostgresDeployPlacementSwarm

## Example Usage

```typescript
import { PostgresDeployPlacementSwarm } from "dokploy-sdk/models/operations";

let value: PostgresDeployPlacementSwarm = {};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `constraints`                                                                                | *string*[]                                                                                   | :heavy_minus_sign:                                                                           | N/A                                                                                          |
| `maxReplicas`                                                                                | *number*                                                                                     | :heavy_minus_sign:                                                                           | N/A                                                                                          |
| `platforms`                                                                                  | [operations.PostgresDeployPlatform](../../models/operations/postgresdeployplatform.md)[]     | :heavy_minus_sign:                                                                           | N/A                                                                                          |
| `preferences`                                                                                | [operations.PostgresDeployPreference](../../models/operations/postgresdeploypreference.md)[] | :heavy_minus_sign:                                                                           | N/A                                                                                          |