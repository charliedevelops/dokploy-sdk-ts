# RedisChangeStatusRequest

## Example Usage

```typescript
import { RedisChangeStatusRequest } from "dokploy-sdk/models/operations";

let value: RedisChangeStatusRequest = {
  applicationStatus: "idle",
  redisId: "<id>",
};
```

## Fields

| Field                                                                                                                        | Type                                                                                                                         | Required                                                                                                                     | Description                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `applicationStatus`                                                                                                          | [operations.RedisChangeStatusApplicationStatusRequest](../../models/operations/redischangestatusapplicationstatusrequest.md) | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |
| `redisId`                                                                                                                    | *string*                                                                                                                     | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |