# NotificationUpdateNtfyRequest

## Example Usage

```typescript
import { NotificationUpdateNtfyRequest } from "dokploy-sdk/models/operations";

let value: NotificationUpdateNtfyRequest = {
  notificationId: "<id>",
  ntfyId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `accessToken`      | *string*           | :heavy_minus_sign: | N/A                |
| `appBuildError`    | *boolean*          | :heavy_minus_sign: | N/A                |
| `appDeploy`        | *boolean*          | :heavy_minus_sign: | N/A                |
| `databaseBackup`   | *boolean*          | :heavy_minus_sign: | N/A                |
| `dockerCleanup`    | *boolean*          | :heavy_minus_sign: | N/A                |
| `dokployRestart`   | *boolean*          | :heavy_minus_sign: | N/A                |
| `name`             | *string*           | :heavy_minus_sign: | N/A                |
| `notificationId`   | *string*           | :heavy_check_mark: | N/A                |
| `ntfyId`           | *string*           | :heavy_check_mark: | N/A                |
| `organizationId`   | *string*           | :heavy_minus_sign: | N/A                |
| `priority`         | *number*           | :heavy_minus_sign: | N/A                |
| `serverUrl`        | *string*           | :heavy_minus_sign: | N/A                |
| `topic`            | *string*           | :heavy_minus_sign: | N/A                |