# DestinationUpdateRequest

## Example Usage

```typescript
import { DestinationUpdateRequest } from "dokploy-sdk/models/operations";

let value: DestinationUpdateRequest = {
  accessKey: "<value>",
  bucket: "<value>",
  destinationId: "<id>",
  endpoint: "<value>",
  name: "<value>",
  provider: null,
  region: "<value>",
  secretAccessKey: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `accessKey`        | *string*           | :heavy_check_mark: | N/A                |
| `bucket`           | *string*           | :heavy_check_mark: | N/A                |
| `destinationId`    | *string*           | :heavy_check_mark: | N/A                |
| `endpoint`         | *string*           | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `provider`         | *string*           | :heavy_check_mark: | N/A                |
| `region`           | *string*           | :heavy_check_mark: | N/A                |
| `secretAccessKey`  | *string*           | :heavy_check_mark: | N/A                |
| `serverId`         | *string*           | :heavy_minus_sign: | N/A                |