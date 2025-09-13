# CertificatesCreateResponseBody

Successful response

## Example Usage

```typescript
import { CertificatesCreateResponseBody } from "dokploy-sdk/models/operations";

let value: CertificatesCreateResponseBody = {
  certificateId: "<id>",
  name: "<value>",
  certificateData: "<value>",
  privateKey: "<value>",
  certificatePath: "<value>",
  autoRenew: true,
  organizationId: "<id>",
  serverId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `certificateId`    | *string*           | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `certificateData`  | *string*           | :heavy_check_mark: | N/A                |
| `privateKey`       | *string*           | :heavy_check_mark: | N/A                |
| `certificatePath`  | *string*           | :heavy_check_mark: | N/A                |
| `autoRenew`        | *boolean*          | :heavy_check_mark: | N/A                |
| `organizationId`   | *string*           | :heavy_check_mark: | N/A                |
| `serverId`         | *string*           | :heavy_check_mark: | N/A                |