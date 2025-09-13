# ApplicationStopRedirect

## Example Usage

```typescript
import { ApplicationStopRedirect } from "dokploy-sdk/models/operations";

let value: ApplicationStopRedirect = {
  redirectId: "<id>",
  regex: "<value>",
  replacement: "<value>",
  permanent: true,
  uniqueConfigKey: 2187.86,
  createdAt: "1707151172424",
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