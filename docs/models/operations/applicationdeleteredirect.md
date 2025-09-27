# ApplicationDeleteRedirect

## Example Usage

```typescript
import { ApplicationDeleteRedirect } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteRedirect = {
  applicationId: "<id>",
  createdAt: "1735112816333",
  permanent: false,
  redirectId: "<id>",
  regex: "<value>",
  replacement: "<value>",
  uniqueConfigKey: 5081.52,
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `applicationId`    | *string*           | :heavy_check_mark: | N/A                |
| `createdAt`        | *string*           | :heavy_check_mark: | N/A                |
| `permanent`        | *boolean*          | :heavy_check_mark: | N/A                |
| `redirectId`       | *string*           | :heavy_check_mark: | N/A                |
| `regex`            | *string*           | :heavy_check_mark: | N/A                |
| `replacement`      | *string*           | :heavy_check_mark: | N/A                |
| `uniqueConfigKey`  | *number*           | :heavy_check_mark: | N/A                |