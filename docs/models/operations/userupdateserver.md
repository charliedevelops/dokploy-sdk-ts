# UserUpdateServer

## Example Usage

```typescript
import { UserUpdateServer } from "dokploy-sdk/models/operations";

let value: UserUpdateServer = {
  cronJob: "<value>",
  port: 2660.27,
  refreshRate: 5166.94,
  retentionDays: 5326.76,
  thresholds: {
    cpu: 7663.31,
    memory: 5312.52,
  },
  token: "<value>",
  type: "Dokploy",
  urlCallback: "<value>",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `cronJob`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `port`                                                                             | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `refreshRate`                                                                      | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `retentionDays`                                                                    | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `thresholds`                                                                       | [operations.UserUpdateThresholds](../../models/operations/userupdatethresholds.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `token`                                                                            | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `type`                                                                             | [operations.UserUpdateType](../../models/operations/userupdatetype.md)             | :heavy_check_mark:                                                                 | N/A                                                                                |
| `urlCallback`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |