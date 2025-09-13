# PostgresChangeStatusRequest

## Example Usage

```typescript
import { PostgresChangeStatusRequest } from "dokploy-sdk/models/operations";

let value: PostgresChangeStatusRequest = {
  postgresId: "<id>",
  applicationStatus: "idle",
};
```

## Fields

| Field                                                                                                                              | Type                                                                                                                               | Required                                                                                                                           | Description                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| `postgresId`                                                                                                                       | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `applicationStatus`                                                                                                                | [operations.PostgresChangeStatusApplicationStatusRequest](../../models/operations/postgreschangestatusapplicationstatusrequest.md) | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |