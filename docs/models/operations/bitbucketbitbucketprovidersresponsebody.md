# BitbucketBitbucketProvidersResponseBody

## Example Usage

```typescript
import { BitbucketBitbucketProvidersResponseBody } from "dokploy-sdk/models/operations";

let value: BitbucketBitbucketProvidersResponseBody = {
  bitbucketId: "<id>",
  gitProvider: {
    createdAt: "1734665593804",
    gitProviderId: "<id>",
    name: "<value>",
    organizationId: "<id>",
    providerType: "gitlab",
    userId: "<id>",
  },
};
```

## Fields

| Field                                                                                                                  | Type                                                                                                                   | Required                                                                                                               | Description                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| `bitbucketId`                                                                                                          | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `gitProvider`                                                                                                          | [operations.BitbucketBitbucketProvidersGitProvider](../../models/operations/bitbucketbitbucketprovidersgitprovider.md) | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |