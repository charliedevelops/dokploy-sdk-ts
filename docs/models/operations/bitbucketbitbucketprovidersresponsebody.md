# BitbucketBitbucketProvidersResponseBody

## Example Usage

```typescript
import { BitbucketBitbucketProvidersResponseBody } from "dokploy-sdk/models/operations";

let value: BitbucketBitbucketProvidersResponseBody = {
  bitbucketId: "<id>",
  gitProvider: {
    gitProviderId: "<id>",
    name: "<value>",
    providerType: "gitea",
    createdAt: "1719022349061",
    organizationId: "<id>",
    userId: "<id>",
  },
};
```

## Fields

| Field                                                                                                                  | Type                                                                                                                   | Required                                                                                                               | Description                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| `bitbucketId`                                                                                                          | *string*                                                                                                               | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |
| `gitProvider`                                                                                                          | [operations.BitbucketBitbucketProvidersGitProvider](../../models/operations/bitbucketbitbucketprovidersgitprovider.md) | :heavy_check_mark:                                                                                                     | N/A                                                                                                                    |