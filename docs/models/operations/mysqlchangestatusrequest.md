# MysqlChangeStatusRequest

## Example Usage

```typescript
import { MysqlChangeStatusRequest } from "dokploy-sdk/models/operations";

let value: MysqlChangeStatusRequest = {
  mysqlId: "<id>",
  applicationStatus: "done",
};
```

## Fields

| Field                                                                                                                        | Type                                                                                                                         | Required                                                                                                                     | Description                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `mysqlId`                                                                                                                    | *string*                                                                                                                     | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |
| `applicationStatus`                                                                                                          | [operations.MysqlChangeStatusApplicationStatusRequest](../../models/operations/mysqlchangestatusapplicationstatusrequest.md) | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |