# ErrorT

Error response

## Example Usage

```typescript
import { ErrorT } from "dokploy-sdk/models";

let value: ErrorT = {
  code: "<value>",
  message: "<value>",
};
```

## Fields

| Field                                | Type                                 | Required                             | Description                          |
| ------------------------------------ | ------------------------------------ | ------------------------------------ | ------------------------------------ |
| `code`                               | *string*                             | :heavy_check_mark:                   | N/A                                  |
| `issues`                             | [models.Issue](../models/issue.md)[] | :heavy_minus_sign:                   | N/A                                  |
| `message`                            | *string*                             | :heavy_check_mark:                   | N/A                                  |