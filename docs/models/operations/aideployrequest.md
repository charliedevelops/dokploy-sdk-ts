# AiDeployRequest

## Example Usage

```typescript
import { AiDeployRequest } from "dokploy-sdk/models/operations";

let value: AiDeployRequest = {
  description: "whenever impossible ick before majestically",
  dockerCompose: "<value>",
  envVariables: "<value>",
  environmentId: "<id>",
  id: "<id>",
  name: "<value>",
};
```

## Fields

| Field                                                                    | Type                                                                     | Required                                                                 | Description                                                              |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| `configFiles`                                                            | [operations.ConfigFile](../../models/operations/configfile.md)[]         | :heavy_minus_sign:                                                       | N/A                                                                      |
| `description`                                                            | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `dockerCompose`                                                          | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `domains`                                                                | [operations.AiDeployDomain](../../models/operations/aideploydomain.md)[] | :heavy_minus_sign:                                                       | N/A                                                                      |
| `envVariables`                                                           | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `environmentId`                                                          | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `id`                                                                     | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `name`                                                                   | *string*                                                                 | :heavy_check_mark:                                                       | N/A                                                                      |
| `serverId`                                                               | *string*                                                                 | :heavy_minus_sign:                                                       | N/A                                                                      |