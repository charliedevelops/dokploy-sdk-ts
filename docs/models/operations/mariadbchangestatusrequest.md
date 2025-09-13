# MariadbChangeStatusRequest

## Example Usage

```typescript
import { MariadbChangeStatusRequest } from "dokploy-sdk/models/operations";

let value: MariadbChangeStatusRequest = {
  mariadbId: "<id>",
  applicationStatus: "done",
};
```

## Fields

| Field                                                                                                                            | Type                                                                                                                             | Required                                                                                                                         | Description                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| `mariadbId`                                                                                                                      | *string*                                                                                                                         | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |
| `applicationStatus`                                                                                                              | [operations.MariadbChangeStatusApplicationStatusRequest](../../models/operations/mariadbchangestatusapplicationstatusrequest.md) | :heavy_check_mark:                                                                                                               | N/A                                                                                                                              |