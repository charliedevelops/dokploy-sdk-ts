# MongoChangeStatusRequest

## Example Usage

```typescript
import { MongoChangeStatusRequest } from "dokploy-sdk/models/operations";

let value: MongoChangeStatusRequest = {
  applicationStatus: "idle",
  mongoId: "<id>",
};
```

## Fields

| Field                                                                                                                        | Type                                                                                                                         | Required                                                                                                                     | Description                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `applicationStatus`                                                                                                          | [operations.MongoChangeStatusApplicationStatusRequest](../../models/operations/mongochangestatusapplicationstatusrequest.md) | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |
| `mongoId`                                                                                                                    | *string*                                                                                                                     | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |