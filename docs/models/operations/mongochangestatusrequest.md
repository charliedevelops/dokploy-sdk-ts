# MongoChangeStatusRequest

## Example Usage

```typescript
import { MongoChangeStatusRequest } from "dokploy-sdk/models/operations";

let value: MongoChangeStatusRequest = {
  mongoId: "<id>",
  applicationStatus: "idle",
};
```

## Fields

| Field                                                                                                                        | Type                                                                                                                         | Required                                                                                                                     | Description                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `mongoId`                                                                                                                    | *string*                                                                                                                     | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |
| `applicationStatus`                                                                                                          | [operations.MongoChangeStatusApplicationStatusRequest](../../models/operations/mongochangestatusapplicationstatusrequest.md) | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |