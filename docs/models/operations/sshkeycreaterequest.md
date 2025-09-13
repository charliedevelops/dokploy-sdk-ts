# SshKeyCreateRequest

## Example Usage

```typescript
import { SshKeyCreateRequest } from "dokploy-sdk/models/operations";

let value: SshKeyCreateRequest = {
  name: "<value>",
  organizationId: "<id>",
  privateKey: "<value>",
  publicKey: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `description`      | *string*           | :heavy_minus_sign: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `organizationId`   | *string*           | :heavy_check_mark: | N/A                |
| `privateKey`       | *string*           | :heavy_check_mark: | N/A                |
| `publicKey`        | *string*           | :heavy_check_mark: | N/A                |