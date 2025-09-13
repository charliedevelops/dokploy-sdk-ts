# NotificationCreateNtfyRequest

## Example Usage

```typescript
import { NotificationCreateNtfyRequest } from "dokploy-sdk/models/operations";

let value: NotificationCreateNtfyRequest = {
  appBuildError: true,
  databaseBackup: true,
  dokployRestart: false,
  name: "<value>",
  appDeploy: true,
  dockerCleanup: true,
  serverUrl: "https://unruly-lender.info",
  topic: "<value>",
  accessToken: "<value>",
  priority: 8921.46,
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
| `topic`            | *string*           | :heavy_check_mark: | N/A                |
| `accessToken`      | *string*           | :heavy_check_mark: | N/A                |
| `priority`         | *number*           | :heavy_check_mark: | N/A                |