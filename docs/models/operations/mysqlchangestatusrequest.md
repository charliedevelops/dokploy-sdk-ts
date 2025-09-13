# MysqlChangeStatusRequest

## Example Usage

```typescript
import { MysqlChangeStatusRequest } from "dokploy-sdk/models/operations";

let value: MysqlChangeStatusRequest = {
  applicationStatus: "done",
  mysqlId: "<id>",
};
```

## Fields

| Field                                                                                                                        | Type                                                                                                                         | Required                                                                                                                     | Description                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `applicationStatus`                                                                                                          | [operations.MysqlChangeStatusApplicationStatusRequest](../../models/operations/mysqlchangestatusapplicationstatusrequest.md) | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |
| `mysqlId`                                                                                                                    | *string*                                                                                                                     | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |