# SettingsAssignDomainServerRequest

## Example Usage

```typescript
import { SettingsAssignDomainServerRequest } from "dokploy-sdk/models/operations";

let value: SettingsAssignDomainServerRequest = {
  certificateType: "custom",
  host: "funny-freckle.biz",
};
```

## Fields

| Field                                                                                                                        | Type                                                                                                                         | Required                                                                                                                     | Description                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `certificateType`                                                                                                            | [operations.SettingsAssignDomainServerCertificateType](../../models/operations/settingsassigndomainservercertificatetype.md) | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |
| `host`                                                                                                                       | *string*                                                                                                                     | :heavy_check_mark:                                                                                                           | N/A                                                                                                                          |
| `https`                                                                                                                      | *boolean*                                                                                                                    | :heavy_minus_sign:                                                                                                           | N/A                                                                                                                          |
| `letsEncryptEmail`                                                                                                           | *string*                                                                                                                     | :heavy_minus_sign:                                                                                                           | N/A                                                                                                                          |