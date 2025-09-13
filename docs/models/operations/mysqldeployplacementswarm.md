# MysqlDeployPlacementSwarm

## Example Usage

```typescript
import { MysqlDeployPlacementSwarm } from "dokploy-sdk/models/operations";

let value: MysqlDeployPlacementSwarm = {};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `constraints`                                                                          | *string*[]                                                                             | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `preferences`                                                                          | [operations.MysqlDeployPreference](../../models/operations/mysqldeploypreference.md)[] | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `maxReplicas`                                                                          | *number*                                                                               | :heavy_minus_sign:                                                                     | N/A                                                                                    |
| `platforms`                                                                            | [operations.MysqlDeployPlatform](../../models/operations/mysqldeployplatform.md)[]     | :heavy_minus_sign:                                                                     | N/A                                                                                    |