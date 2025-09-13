# NotificationCreateTelegramRequest

## Example Usage

```typescript
import { NotificationCreateTelegramRequest } from "dokploy-sdk/models/operations";

let value: NotificationCreateTelegramRequest = {
  appBuildError: true,
  databaseBackup: false,
  dokployRestart: true,
  name: "<value>",
  appDeploy: true,
  dockerCleanup: false,
  serverThreshold: false,
  botToken: "<value>",
  chatId: "<id>",
  messageThreadId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `appBuildError`    | *boolean*          | :heavy_check_mark: | N/A                |
| `databaseBackup`   | *boolean*          | :heavy_check_mark: | N/A                |
| `dokployRestart`   | *boolean*          | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `appDeploy`        | *boolean*          | :heavy_check_mark: | N/A                |
| `dockerCleanup`    | *boolean*          | :heavy_check_mark: | N/A                |
| `serverThreshold`  | *boolean*          | :heavy_check_mark: | N/A                |
| `botToken`         | *string*           | :heavy_check_mark: | N/A                |
| `chatId`           | *string*           | :heavy_check_mark: | N/A                |
| `messageThreadId`  | *string*           | :heavy_check_mark: | N/A                |