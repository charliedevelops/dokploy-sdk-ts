# NotificationCreateDiscordRequest

## Example Usage

```typescript
import { NotificationCreateDiscordRequest } from "dokploy-sdk/models/operations";

let value: NotificationCreateDiscordRequest = {
  appBuildError: false,
  databaseBackup: true,
  dokployRestart: false,
  name: "<value>",
  appDeploy: true,
  dockerCleanup: false,
  serverThreshold: false,
  webhookUrl: "https://other-surface.info",
  decoration: false,
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
| `webhookUrl`       | *string*           | :heavy_check_mark: | N/A                |
| `decoration`       | *boolean*          | :heavy_check_mark: | N/A                |