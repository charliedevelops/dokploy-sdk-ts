# NotificationUpdateDiscordRequest

## Example Usage

```typescript
import { NotificationUpdateDiscordRequest } from "dokploy-sdk/models/operations";

let value: NotificationUpdateDiscordRequest = {
  discordId: "<id>",
  notificationId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `appBuildError`    | *boolean*          | :heavy_minus_sign: | N/A                |
| `appDeploy`        | *boolean*          | :heavy_minus_sign: | N/A                |
| `databaseBackup`   | *boolean*          | :heavy_minus_sign: | N/A                |
| `decoration`       | *boolean*          | :heavy_minus_sign: | N/A                |
| `discordId`        | *string*           | :heavy_check_mark: | N/A                |
| `dockerCleanup`    | *boolean*          | :heavy_minus_sign: | N/A                |
| `dokployRestart`   | *boolean*          | :heavy_minus_sign: | N/A                |
| `name`             | *string*           | :heavy_minus_sign: | N/A                |
| `notificationId`   | *string*           | :heavy_check_mark: | N/A                |
| `organizationId`   | *string*           | :heavy_minus_sign: | N/A                |
| `serverThreshold`  | *boolean*          | :heavy_minus_sign: | N/A                |
| `webhookUrl`       | *string*           | :heavy_minus_sign: | N/A                |