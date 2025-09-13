# AiDeployRequest

## Example Usage

```typescript
import { AiDeployRequest } from "dokploy-sdk/models/operations";

let value: AiDeployRequest = {
  environmentId: "<id>",
  id: "<id>",
  dockerCompose: "<value>",
  envVariables: "<value>",
  name: "<value>",
  description: "whenever impossible ick before majestically",
};
```

## Fields

| Field                                                                    | Type                                                                     | Required                                                                 | Description                                                              |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| `environmentId`                                                          | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `id`                                                                     | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `dockerCompose`                                                          | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `envVariables`                                                           | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `serverId`                                                               | *string*                                                                 | :heavy_minus_sign:                                                       | N/A                                                                      |
| `name`                                                                   | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `description`                                                            | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `domains`                                                                | [operations.AiDeployDomain](../../models/operations/aideploydomain.md)[] | :heavy_minus_sign:                                                       | N/A                                                                      |
| `configFiles`                                                            | [operations.ConfigFile](../../models/operations/configfile.md)[]         | :heavy_minus_sign:                                                       | N/A                                                                      |