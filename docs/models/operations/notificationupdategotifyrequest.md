# NotificationUpdateGotifyRequest

## Example Usage

```typescript
import { NotificationUpdateGotifyRequest } from "dokploy-sdk/models/operations";

let value: NotificationUpdateGotifyRequest = {
  gotifyId: "<id>",
  notificationId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `appBuildError`    | *boolean*          | :heavy_minus_sign: | N/A                |
| `appDeploy`        | *boolean*          | :heavy_minus_sign: | N/A                |
| `appToken`         | *string*           | :heavy_minus_sign: | N/A                |
| `databaseBackup`   | *boolean*          | :heavy_minus_sign: | N/A                |
| `decoration`       | *boolean*          | :heavy_minus_sign: | N/A                |
| `dockerCleanup`    | *boolean*          | :heavy_minus_sign: | N/A                |
| `dokployRestart`   | *boolean*          | :heavy_minus_sign: | N/A                |
| `gotifyId`         | *string*           | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_minus_sign: | N/A                |
| `notificationId`   | *string*           | :heavy_check_mark: | N/A                |
| `organizationId`   | *string*           | :heavy_minus_sign: | N/A                |
| `priority`         | *number*           | :heavy_minus_sign: | N/A                |
| `serverUrl`        | *string*           | :heavy_minus_sign: | N/A                |