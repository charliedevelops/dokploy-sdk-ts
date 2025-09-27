# ApplicationOneRedirect

## Example Usage

```typescript
import { ApplicationOneRedirect } from "dokploy-sdk/models/operations";

let value: ApplicationOneRedirect = {
  applicationId: "<id>",
  createdAt: "1706184679783",
  permanent: true,
  redirectId: "<id>",
  regex: "<value>",
  replacement: "<value>",
  uniqueConfigKey: 3072.36,
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