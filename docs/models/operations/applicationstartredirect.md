# ApplicationStartRedirect

## Example Usage

```typescript
import { ApplicationStartRedirect } from "dokploy-sdk/models/operations";

let value: ApplicationStartRedirect = {
  applicationId: "<id>",
  createdAt: "1733117124364",
  permanent: true,
  redirectId: "<id>",
  regex: "<value>",
  replacement: "<value>",
  uniqueConfigKey: 1274.92,
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