# UserUpdateServer

## Example Usage

```typescript
import { UserUpdateServer } from "dokploy-sdk/models/operations";

let value: UserUpdateServer = {
  type: "Dokploy",
  refreshRate: 5166.94,
  port: 5326.76,
  token: "<value>",
  urlCallback: "<value>",
  retentionDays: 7663.31,
  cronJob: "<value>",
  thresholds: {
    cpu: 5312.52,
    memory: 790.33,
  },
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `type`                                                                             | [operations.UserUpdateType](../../models/operations/userupdatetype.md)             | :heavy_check_mark:                                                                 | N/A                                                                                |
| `refreshRate`                                                                      | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `port`                                                                             | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `token`                                                                            | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `urlCallback`                                                                      | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `retentionDays`                                                                    | *number*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `cronJob`                                                                          | *string*                                                                           | :heavy_check_mark:                                                                 | N/A                                                                                |
| `thresholds`                                                                       | [operations.UserUpdateThresholds](../../models/operations/userupdatethresholds.md) | :heavy_check_mark:                                                                 | N/A                                                                                |