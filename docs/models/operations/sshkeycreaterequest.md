# SshKeyCreateRequest

## Example Usage

```typescript
import { SshKeyCreateRequest } from "dokploy-sdk/models/operations";

let value: SshKeyCreateRequest = {
  name: "<value>",
  privateKey: "<value>",
  publicKey: "<value>",
  organizationId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `description`      | *string*           | :heavy_minus_sign: | N/A                |
| `privateKey`       | *string*           | :heavy_check_mark: | N/A                |
| `publicKey`        | *string*           | :heavy_check_mark: | N/A                |
| `organizationId`   | *string*           | :heavy_check_mark: | N/A                |