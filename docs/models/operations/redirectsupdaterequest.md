# RedirectsUpdateRequest

## Example Usage

```typescript
import { RedirectsUpdateRequest } from "dokploy-sdk/models/operations";

let value: RedirectsUpdateRequest = {
  permanent: false,
  redirectId: "<id>",
  regex: "<value>",
  replacement: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `permanent`        | *boolean*          | :heavy_check_mark: | N/A                |
| `redirectId`       | *string*           | :heavy_check_mark: | N/A                |
| `regex`            | *string*           | :heavy_check_mark: | N/A                |
| `replacement`      | *string*           | :heavy_check_mark: | N/A                |