# NotificationCreateGotifyRequest

## Example Usage

```typescript
import { NotificationCreateGotifyRequest } from "dokploy-sdk/models/operations";

let value: NotificationCreateGotifyRequest = {
  appBuildError: false,
  databaseBackup: true,
  dokployRestart: true,
  name: "<value>",
  appDeploy: false,
  dockerCleanup: false,
  serverUrl: "https://insidious-disclosure.net/",
  appToken: "<value>",
  priority: 5065.66,
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
| `serverUrl`        | *string*           | :heavy_check_mark: | N/A                |
| `appToken`         | *string*           | :heavy_check_mark: | N/A                |
| `priority`         | *number*           | :heavy_check_mark: | N/A                |
| `decoration`       | *boolean*          | :heavy_check_mark: | N/A                |