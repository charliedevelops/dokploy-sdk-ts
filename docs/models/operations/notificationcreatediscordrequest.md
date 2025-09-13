# NotificationCreateDiscordRequest

## Example Usage

```typescript
import { NotificationCreateDiscordRequest } from "dokploy-sdk/models/operations";

let value: NotificationCreateDiscordRequest = {
  appBuildError: false,
  appDeploy: true,
  databaseBackup: false,
  decoration: true,
  dockerCleanup: false,
  dokployRestart: false,
  name: "<value>",
  serverThreshold: false,
  webhookUrl: "https://trusty-incandescence.name",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `appBuildError`    | *boolean*          | :heavy_check_mark: | N/A                |
| `appDeploy`        | *boolean*          | :heavy_check_mark: | N/A                |
| `databaseBackup`   | *boolean*          | :heavy_check_mark: | N/A                |
| `decoration`       | *boolean*          | :heavy_check_mark: | N/A                |
| `dockerCleanup`    | *boolean*          | :heavy_check_mark: | N/A                |
| `dokployRestart`   | *boolean*          | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `serverThreshold`  | *boolean*          | :heavy_check_mark: | N/A                |
| `webhookUrl`       | *string*           | :heavy_check_mark: | N/A                |