# SettingsAssignDomainServerRequest

## Example Usage

```typescript
import { SettingsAssignDomainServerRequest } from "dokploy-sdk/models/operations";

let value: SettingsAssignDomainServerRequest = {
  host: "corrupt-exhaust.info",
  certificateType: "letsencrypt",
};
```

## Fields

| Field                                                                                                                        | Type                                                                                                                         | Required                                                                                                                     | Description                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `host`                                                                                                                       | *string*                                                                                                                     | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |
| `certificateType`                                                                                                            | [operations.SettingsAssignDomainServerCertificateType](../../models/operations/settingsassigndomainservercertificatetype.md) | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |
| `letsEncryptEmail`                                                                                                           | *string*                                                                                                                     | :heavy_minus_sign:                                                                                                           | N/A                                                                                                                          |
| `https`                                                                                                                      | *boolean*                                                                                                                    | :heavy_minus_sign:                                                                                                           | N/A                                                                                                                          |