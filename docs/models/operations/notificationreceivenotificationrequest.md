# NotificationReceiveNotificationRequest

## Example Usage

```typescript
import { NotificationReceiveNotificationRequest } from "dokploy-sdk/models/operations";

let value: NotificationReceiveNotificationRequest = {
  message: "<value>",
  threshold: 4520.66,
  timestamp: "<value>",
  token: "<value>",
  type: "Memory",
  value: 1163.74,
};
```

## Fields

| Field                                                                                                            | Type                                                                                                             | Required                                                                                                         | Description                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `message`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `serverType`                                                                                                     | [operations.ServerType](../../models/operations/servertype.md)                                                   | :heavy_minus_sign:                                                                                               | N/A                                                                                                              |
| `threshold`                                                                                                      | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `timestamp`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `token`                                                                                                          | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `type`                                                                                                           | [operations.NotificationReceiveNotificationType](../../models/operations/notificationreceivenotificationtype.md) | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `value`                                                                                                          | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |