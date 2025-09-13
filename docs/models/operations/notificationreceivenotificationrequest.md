# NotificationReceiveNotificationRequest

## Example Usage

```typescript
import { NotificationReceiveNotificationRequest } from "dokploy-sdk/models/operations";

let value: NotificationReceiveNotificationRequest = {
  type: "Memory",
  value: 294.58,
  threshold: 1163.74,
  message: "<value>",
  timestamp: "<value>",
  token: "<value>",
};
```

## Fields

| Field                                                                                                            | Type                                                                                                             | Required                                                                                                         | Description                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| `serverType`                                                                                                     | [operations.ServerType](../../models/operations/servertype.md)                                                   | :heavy_minus_sign:                                                                                               | N/A                                                                                                              |
| `type`                                                                                                           | [operations.NotificationReceiveNotificationType](../../models/operations/notificationreceivenotificationtype.md) | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `value`                                                                                                          | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `threshold`                                                                                                      | *number*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `message`                                                                                                        | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `timestamp`                                                                                                      | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |
| `token`                                                                                                          | *string*                                                                                                         | :heavy_check_mark:                                                                                               | N/A                                                                                                              |