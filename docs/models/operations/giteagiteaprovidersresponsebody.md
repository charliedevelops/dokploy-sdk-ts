# GiteaGiteaProvidersResponseBody

## Example Usage

```typescript
import { GiteaGiteaProvidersResponseBody } from "dokploy-sdk/models/operations";

let value: GiteaGiteaProvidersResponseBody = {
  giteaId: "<id>",
  gitProvider: {
    gitProviderId: "<id>",
    name: "<value>",
    providerType: "github",
    createdAt: "1715522586443",
    organizationId: "<id>",
    userId: "<id>",
  },
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `giteaId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `gitProvider`                                                                                          | [operations.GiteaGiteaProvidersGitProvider](../../models/operations/giteagiteaprovidersgitprovider.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |