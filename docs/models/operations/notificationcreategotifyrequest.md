# NotificationCreateGotifyRequest

## Example Usage

```typescript
import { NotificationCreateGotifyRequest } from "dokploy-sdk/models/operations";

let value: NotificationCreateGotifyRequest = {
  appBuildError: false,
  appDeploy: true,
  appToken: "<value>",
  databaseBackup: true,
  decoration: false,
  dockerCleanup: false,
  dokployRestart: true,
  name: "<value>",
  priority: 4223.98,
  serverUrl: "https://recent-lace.net/",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `appBuildError`    | *boolean*          | :heavy_check_mark: | N/A                |
| `appDeploy`        | *boolean*          | :heavy_check_mark: | N/A                |
| `appToken`         | *string*           | :heavy_check_mark: | N/A                |
| `databaseBackup`   | *boolean*          | :heavy_check_mark: | N/A                |
| `decoration`       | *boolean*          | :heavy_check_mark: | N/A                |
| `dockerCleanup`    | *boolean*          | :heavy_check_mark: | N/A                |
| `dokployRestart`   | *boolean*          | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `priority`         | *number*           | :heavy_check_mark: | N/A                |
| `serverUrl`        | *string*           | :heavy_check_mark: | N/A                |