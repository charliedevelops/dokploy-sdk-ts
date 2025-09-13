# MysqlStartPlacementSwarm

## Example Usage

```typescript
import { MysqlStartPlacementSwarm } from "dokploy-sdk/models/operations";

let value: MysqlStartPlacementSwarm = {};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `constraints`                                                                        | *string*[]                                                                           | :heavy_minus_sign:                                                                   | N/A                                                                                  |
| `maxReplicas`                                                                        | *number*                                                                             | :heavy_minus_sign:                                                                   | N/A                                                                                  |
| `platforms`                                                                          | [operations.MysqlStartPlatform](../../models/operations/mysqlstartplatform.md)[]     | :heavy_minus_sign:                                                                   | N/A                                                                                  |
| `preferences`                                                                        | [operations.MysqlStartPreference](../../models/operations/mysqlstartpreference.md)[] | :heavy_minus_sign:                                                                   | N/A                                                                                  |