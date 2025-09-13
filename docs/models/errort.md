# ErrorT

Error response

## Example Usage

```typescript
import { ErrorT } from "dokploy-sdk/models";

let value: ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

## Fields

| Field                                | Type                                 | Required                             | Description                          |
| ------------------------------------ | ------------------------------------ | ------------------------------------ | ------------------------------------ |
| `message`                            | *string*                             | :heavy_check_mark:                   | N/A                                  |
| `code`                               | *string*                             | :heavy_check_mark:                   | N/A                                  |
| `issues`                             | [models.Issue](../models/issue.md)[] | :heavy_minus_sign:                   | N/A                                  |