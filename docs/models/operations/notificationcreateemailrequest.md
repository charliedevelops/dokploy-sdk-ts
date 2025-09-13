# NotificationCreateEmailRequest

## Example Usage

```typescript
import { NotificationCreateEmailRequest } from "dokploy-sdk/models/operations";

let value: NotificationCreateEmailRequest = {
  appBuildError: false,
  appDeploy: true,
  databaseBackup: true,
  dockerCleanup: false,
  dokployRestart: true,
  fromAddress: "<value>",
  name: "<value>",
  password: "S_Zxu4oWSujorkp",
  serverThreshold: false,
  smtpPort: 2069.09,
  smtpServer: "<value>",
  toAddresses: [],
  username: "Terrence.Skiles",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `appBuildError`    | *boolean*          | :heavy_check_mark: | N/A                |
| `appDeploy`        | *boolean*          | :heavy_check_mark: | N/A                |
| `databaseBackup`   | *boolean*          | :heavy_check_mark: | N/A                |
| `dockerCleanup`    | *boolean*          | :heavy_check_mark: | N/A                |
| `dokployRestart`   | *boolean*          | :heavy_check_mark: | N/A                |
| `fromAddress`      | *string*           | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `password`         | *string*           | :heavy_check_mark: | N/A                |
| `serverThreshold`  | *boolean*          | :heavy_check_mark: | N/A                |
| `smtpPort`         | *number*           | :heavy_check_mark: | N/A                |
| `smtpServer`       | *string*           | :heavy_check_mark: | N/A                |
| `toAddresses`      | *string*[]         | :heavy_check_mark: | N/A                |
| `username`         | *string*           | :heavy_check_mark: | N/A                |