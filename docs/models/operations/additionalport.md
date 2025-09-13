# AdditionalPort

## Example Usage

```typescript
import { AdditionalPort } from "dokploy-sdk/models/operations";

let value: AdditionalPort = {
  targetPort: 7531.81,
  publishedPort: 6096.12,
  protocol: "tcp",
};
```

## Fields

| Field                                                                                                          | Type                                                                                                           | Required                                                                                                       | Description                                                                                                    |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| `targetPort`                                                                                                   | *number*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `publishedPort`                                                                                                | *number*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `protocol`                                                                                                     | [operations.SettingsUpdateTraefikPortsProtocol](../../models/operations/settingsupdatetraefikportsprotocol.md) | :heavy_check_mark:                                                                                             | N/A                                                                                                            |