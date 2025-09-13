# PostgresChangeStatusRequest

## Example Usage

```typescript
import { PostgresChangeStatusRequest } from "dokploy-sdk/models/operations";

let value: PostgresChangeStatusRequest = {
  applicationStatus: "idle",
  postgresId: "<id>",
};
```

## Fields

| Field                                                                                                                              | Type                                                                                                                               | Required                                                                                                                           | Description                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| `applicationStatus`                                                                                                                | [operations.PostgresChangeStatusApplicationStatusRequest](../../models/operations/postgreschangestatusapplicationstatusrequest.md) | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |
| `postgresId`                                                                                                                       | *string*                                                                                                                           | :heavy_check_mark:                                                                                                                 | N/A                                                                                                                                |