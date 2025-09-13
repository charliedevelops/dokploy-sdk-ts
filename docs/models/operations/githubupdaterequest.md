# GithubUpdateRequest

## Example Usage

```typescript
import { GithubUpdateRequest } from "dokploy-sdk/models/operations";

let value: GithubUpdateRequest = {
  gitProviderId: "<id>",
  githubId: "<id>",
  name: "<value>",
};
```

## Fields

| Field                  | Type                   | Required               | Description            |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| `gitProviderId`        | *string*               | :heavy_check_mark:     | N/A                    |
| `githubAppId`          | *number*               | :heavy_minus_sign:     | N/A                    |
| `githubAppName`        | *string*               | :heavy_minus_sign:     | N/A                    |
| `githubClientId`       | *string*               | :heavy_minus_sign:     | N/A                    |
| `githubClientSecret`   | *string*               | :heavy_minus_sign:     | N/A                    |
| `githubId`             | *string*               | :heavy_check_mark:     | N/A                    |
| `githubInstallationId` | *string*               | :heavy_minus_sign:     | N/A                    |
| `githubPrivateKey`     | *string*               | :heavy_minus_sign:     | N/A                    |
| `githubWebhookSecret`  | *string*               | :heavy_minus_sign:     | N/A                    |
| `name`                 | *string*               | :heavy_check_mark:     | N/A                    |