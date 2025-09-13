# NotificationUpdateEmailRequest

## Example Usage

```typescript
import { NotificationUpdateEmailRequest } from "dokploy-sdk/models/operations";

let value: NotificationUpdateEmailRequest = {
  emailId: "<id>",
  notificationId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `appBuildError`    | *boolean*          | :heavy_minus_sign: | N/A                |
| `appDeploy`        | *boolean*          | :heavy_minus_sign: | N/A                |
| `databaseBackup`   | *boolean*          | :heavy_minus_sign: | N/A                |
| `dockerCleanup`    | *boolean*          | :heavy_minus_sign: | N/A                |
| `dokployRestart`   | *boolean*          | :heavy_minus_sign: | N/A                |
| `emailId`          | *string*           | :heavy_check_mark: | N/A                |
| `fromAddress`      | *string*           | :heavy_minus_sign: | N/A                |
| `name`             | *string*           | :heavy_minus_sign: | N/A                |
| `notificationId`   | *string*           | :heavy_check_mark: | N/A                |
| `organizationId`   | *string*           | :heavy_minus_sign: | N/A                |
| `password`         | *string*           | :heavy_minus_sign: | N/A                |
| `serverThreshold`  | *boolean*          | :heavy_minus_sign: | N/A                |
| `smtpPort`         | *number*           | :heavy_minus_sign: | N/A                |
| `smtpServer`       | *string*           | :heavy_minus_sign: | N/A                |
| `toAddresses`      | *string*[]         | :heavy_minus_sign: | N/A                |
| `username`         | *string*           | :heavy_minus_sign: | N/A                |