# ServerUpdateRequest

## Example Usage

```typescript
import { ServerUpdateRequest } from "dokploy-sdk/models/operations";

let value: ServerUpdateRequest = {
  name: "<value>",
  serverId: "<id>",
  ipAddress: "caa8:1be3:b423:e65b:268e:e9be:42eb:94a0",
  port: 5420.14,
  username: "Ryann_Weissnat73",
  sshKeyId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `description`      | *string*           | :heavy_minus_sign: | N/A                |
| `serverId`         | *string*           | :heavy_check_mark: | N/A                |
| `ipAddress`        | *string*           | :heavy_check_mark: | N/A                |
| `port`             | *number*           | :heavy_check_mark: | N/A                |
| `username`         | *string*           | :heavy_check_mark: | N/A                |
| `sshKeyId`         | *string*           | :heavy_check_mark: | N/A                |
| `command`          | *string*           | :heavy_minus_sign: | N/A                |