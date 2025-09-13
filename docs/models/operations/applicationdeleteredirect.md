# ApplicationDeleteRedirect

## Example Usage

```typescript
import { ApplicationDeleteRedirect } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteRedirect = {
  redirectId: "<id>",
  regex: "<value>",
  replacement: "<value>",
  permanent: false,
  uniqueConfigKey: 9871.39,
  createdAt: "1720178665675",
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