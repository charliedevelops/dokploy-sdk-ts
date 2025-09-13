# NotificationTestEmailConnectionRequest

## Example Usage

```typescript
import { NotificationTestEmailConnectionRequest } from "dokploy-sdk/models/operations";

let value: NotificationTestEmailConnectionRequest = {
  smtpServer: "<value>",
  smtpPort: 364.16,
  username: "Nadia_Ankunding25",
  password: "5PL6U1ez0w7XvQ1",
  toAddresses: [
    "<value 1>",
  ],
  fromAddress: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `smtpServer`       | *string*           | :heavy_check_mark: | N/A                |
| `smtpPort`         | *number*           | :heavy_check_mark: | N/A                |
| `username`         | *string*           | :heavy_check_mark: | N/A                |
| `password`         | *string*           | :heavy_check_mark: | N/A                |
| `toAddresses`      | *string*[]         | :heavy_check_mark: | N/A                |
| `fromAddress`      | *string*           | :heavy_check_mark: | N/A                |