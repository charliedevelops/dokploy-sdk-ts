# NotificationCreateNtfyRequest

## Example Usage

```typescript
import { NotificationCreateNtfyRequest } from "dokploy-sdk/models/operations";

let value: NotificationCreateNtfyRequest = {
  accessToken: "<value>",
  appBuildError: true,
  appDeploy: true,
  databaseBackup: false,
  dockerCleanup: true,
  dokployRestart: true,
  name: "<value>",
  priority: 9879.54,
  serverUrl: "https://misguided-independence.org",
  topic: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `accessToken`      | *string*           | :heavy_check_mark: | N/A                |
| `appBuildError`    | *boolean*          | :heavy_check_mark: | N/A                |
| `appDeploy`        | *boolean*          | :heavy_check_mark: | N/A                |
| `databaseBackup`   | *boolean*          | :heavy_check_mark: | N/A                |
| `dockerCleanup`    | *boolean*          | :heavy_check_mark: | N/A                |
| `dokployRestart`   | *boolean*          | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `priority`         | *number*           | :heavy_check_mark: | N/A                |
| `serverUrl`        | *string*           | :heavy_check_mark: | N/A                |
| `topic`            | *string*           | :heavy_check_mark: | N/A                |