# RedirectsCreateResponseBody

Successful response

## Example Usage

```typescript
import { RedirectsCreateResponseBody } from "dokploy-sdk/models/operations";

let value: RedirectsCreateResponseBody = {
  redirectId: "<id>",
  regex: "<value>",
  replacement: "<value>",
  permanent: false,
  uniqueConfigKey: 3711.14,
  createdAt: "1708490172976",
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