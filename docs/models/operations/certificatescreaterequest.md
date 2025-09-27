# CertificatesCreateRequest

## Example Usage

```typescript
import { CertificatesCreateRequest } from "dokploy-sdk/models/operations";

let value: CertificatesCreateRequest = {
  certificateData: "<value>",
  name: "<value>",
  organizationId: "<id>",
  privateKey: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `autoRenew`        | *boolean*          | :heavy_minus_sign: | N/A                |
| `certificateData`  | *string*           | :heavy_check_mark: | N/A                |
| `certificateId`    | *string*           | :heavy_minus_sign: | N/A                |
| `certificatePath`  | *string*           | :heavy_minus_sign: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `organizationId`   | *string*           | :heavy_check_mark: | N/A                |
| `privateKey`       | *string*           | :heavy_check_mark: | N/A                |
| `serverId`         | *string*           | :heavy_minus_sign: | N/A                |