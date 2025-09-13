# SettingsUpdateTraefikPortsRequest

## Example Usage

```typescript
import { SettingsUpdateTraefikPortsRequest } from "dokploy-sdk/models/operations";

let value: SettingsUpdateTraefikPortsRequest = {
  additionalPorts: [],
};
```

## Fields

| Field                                                                    | Type                                                                     | Required                                                                 | Description                                                              |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| `serverId`                                                               | *string*                                                                 | :heavy_minus_sign:                                                       | N/A                                                                      |
| `additionalPorts`                                                        | [operations.AdditionalPort](../../models/operations/additionalport.md)[] | :heavy_check_mark:                                                       | N/A                                                                      |