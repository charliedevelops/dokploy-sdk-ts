# UserUpdateContainers

## Example Usage

```typescript
import { UserUpdateContainers } from "dokploy-sdk/models/operations";

let value: UserUpdateContainers = {
  refreshRate: 7558.07,
  services: {
    include: [],
    exclude: [
      "<value 1>",
      "<value 2>",
    ],
  },
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `refreshRate`                                                                  | *number*                                                                       | :heavy_check_mark:                                                             | N/A                                                                            |
| `services`                                                                     | [operations.UserUpdateServices](../../models/operations/userupdateservices.md) | :heavy_check_mark:                                                             | N/A                                                                            |