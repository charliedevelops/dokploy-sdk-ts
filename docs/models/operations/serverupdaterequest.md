# ServerUpdateRequest

## Example Usage

```typescript
import { ServerUpdateRequest } from "dokploy-sdk/models/operations";

let value: ServerUpdateRequest = {
  ipAddress: "caa8:1be3:b423:e65b:268e:e9be:42eb:94a0",
  name: "<value>",
  port: 5420.14,
  serverId: "<id>",
  sshKeyId: "<id>",
  username: "Lenore23",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `command`          | *string*           | :heavy_minus_sign: | N/A                |
| `description`      | *string*           | :heavy_minus_sign: | N/A                |
| `ipAddress`        | *string*           | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `port`             | *number*           | :heavy_check_mark: | N/A                |
| `serverId`         | *string*           | :heavy_check_mark: | N/A                |
| `sshKeyId`         | *string*           | :heavy_check_mark: | N/A                |
| `username`         | *string*           | :heavy_check_mark: | N/A                |