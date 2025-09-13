# ServerCreateRequest

## Example Usage

```typescript
import { ServerCreateRequest } from "dokploy-sdk/models/operations";

let value: ServerCreateRequest = {
  name: "<value>",
  ipAddress: "196.227.162.169",
  port: 682.98,
  username: "Jordi79",
  sshKeyId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `description`      | *string*           | :heavy_minus_sign: | N/A                |
| `ipAddress`        | *string*           | :heavy_check_mark: | N/A                |
| `port`             | *number*           | :heavy_check_mark: | N/A                |
| `username`         | *string*           | :heavy_check_mark: | N/A                |
| `sshKeyId`         | *string*           | :heavy_check_mark: | N/A                |