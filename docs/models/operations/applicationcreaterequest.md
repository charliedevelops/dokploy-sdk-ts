# ApplicationCreateRequest

## Example Usage

```typescript
import { ApplicationCreateRequest } from "dokploy-sdk/models/operations";

let value: ApplicationCreateRequest = {
  name: "<value>",
  environmentId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `name`             | *string*           | :heavy_check_mark: | N/A                |
| `appName`          | *string*           | :heavy_minus_sign: | N/A                |
| `description`      | *string*           | :heavy_minus_sign: | N/A                |
| `environmentId`    | *string*           | :heavy_check_mark: | N/A                |
| `serverId`         | *string*           | :heavy_minus_sign: | N/A                |