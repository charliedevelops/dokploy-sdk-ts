# RedirectsUpdateRequest

## Example Usage

```typescript
import { RedirectsUpdateRequest } from "dokploy-sdk/models/operations";

let value: RedirectsUpdateRequest = {
  redirectId: "<id>",
  regex: "<value>",
  replacement: "<value>",
  permanent: false,
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `redirectId`       | *string*           | :heavy_check_mark: | N/A                |
| `regex`            | *string*           | :heavy_check_mark: | N/A                |
| `replacement`      | *string*           | :heavy_check_mark: | N/A                |
| `permanent`        | *boolean*          | :heavy_check_mark: | N/A                |