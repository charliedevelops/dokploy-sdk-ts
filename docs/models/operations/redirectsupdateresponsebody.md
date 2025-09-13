# RedirectsUpdateResponseBody

Successful response

## Example Usage

```typescript
import { RedirectsUpdateResponseBody } from "dokploy-sdk/models/operations";

let value: RedirectsUpdateResponseBody = {
  redirectId: "<id>",
  regex: "<value>",
  replacement: "<value>",
  permanent: false,
  uniqueConfigKey: 3240.08,
  createdAt: "1723319638594",
  applicationId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `redirectId`       | *string*           | :heavy_check_mark: | N/A                |
| `regex`            | *string*           | :heavy_check_mark: | N/A                |
| `replacement`      | *string*           | :heavy_check_mark: | N/A                |
| `permanent`        | *boolean*          | :heavy_check_mark: | N/A                |
| `uniqueConfigKey`  | *number*           | :heavy_check_mark: | N/A                |
| `createdAt`        | *string*           | :heavy_check_mark: | N/A                |
| `applicationId`    | *string*           | :heavy_check_mark: | N/A                |