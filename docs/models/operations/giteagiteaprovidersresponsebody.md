# GiteaGiteaProvidersResponseBody

## Example Usage

```typescript
import { GiteaGiteaProvidersResponseBody } from "dokploy-sdk/models/operations";

let value: GiteaGiteaProvidersResponseBody = {
  gitProvider: {
    createdAt: "1711586805857",
    gitProviderId: "<id>",
    name: "<value>",
    organizationId: "<id>",
    providerType: "gitlab",
    userId: "<id>",
  },
  giteaId: "<id>",
};
```

## Fields

| Field                                                                                                  | Type                                                                                                   | Required                                                                                               | Description                                                                                            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| `gitProvider`                                                                                          | [operations.GiteaGiteaProvidersGitProvider](../../models/operations/giteagiteaprovidersgitprovider.md) | :heavy_check_mark:                                                                                     | N/A                                                                                                    |
| `giteaId`                                                                                              | *string*                                                                                               | :heavy_check_mark:                                                                                     | N/A                                                                                                    |