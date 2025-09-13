# NotificationCreateSlackRequest

## Example Usage

```typescript
import { NotificationCreateSlackRequest } from "dokploy-sdk/models/operations";

let value: NotificationCreateSlackRequest = {
  appBuildError: true,
  appDeploy: true,
  channel: "<value>",
  databaseBackup: false,
  dockerCleanup: false,
  dokployRestart: false,
  name: "<value>",
  serverThreshold: false,
  webhookUrl: "https://spotless-ravioli.com/",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `appBuildError`    | *boolean*          | :heavy_check_mark: | N/A                |
| `appDeploy`        | *boolean*          | :heavy_check_mark: | N/A                |
| `channel`          | *string*           | :heavy_check_mark: | N/A                |
| `databaseBackup`   | *boolean*          | :heavy_check_mark: | N/A                |
| `dockerCleanup`    | *boolean*          | :heavy_check_mark: | N/A                |
| `dokployRestart`   | *boolean*          | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `serverThreshold`  | *boolean*          | :heavy_check_mark: | N/A                |
| `webhookUrl`       | *string*           | :heavy_check_mark: | N/A                |