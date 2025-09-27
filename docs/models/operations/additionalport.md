# AdditionalPort

## Example Usage

```typescript
import { AdditionalPort } from "dokploy-sdk/models/operations";

let value: AdditionalPort = {
  protocol: "sctp",
  publishedPort: 6096.12,
  targetPort: 3039.32,
};
```

## Fields

| Field                                                                                                          | Type                                                                                                           | Required                                                                                                       | Description                                                                                                    |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| `protocol`                                                                                                     | [operations.SettingsUpdateTraefikPortsProtocol](../../models/operations/settingsupdatetraefikportsprotocol.md) | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `publishedPort`                                                                                                | *number*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |
| `targetPort`                                                                                                   | *number*                                                                                                       | :heavy_check_mark:                                                                                             | N/A                                                                                                            |