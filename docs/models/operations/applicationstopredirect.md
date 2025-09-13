# ApplicationStopRedirect

## Example Usage

```typescript
import { ApplicationStopRedirect } from "dokploy-sdk/models/operations";

let value: ApplicationStopRedirect = {
  applicationId: "<id>",
  createdAt: "1708833180591",
  permanent: true,
  redirectId: "<id>",
  regex: "<value>",
  replacement: "<value>",
  uniqueConfigKey: 950.52,
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