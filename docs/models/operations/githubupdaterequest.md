# GithubUpdateRequest

## Example Usage

```typescript
import { GithubUpdateRequest } from "dokploy-sdk/models/operations";

let value: GithubUpdateRequest = {
  githubId: "<id>",
  gitProviderId: "<id>",
  name: "<value>",
};
```

## Fields

| Field                  | Type                   | Required               | Description            |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
| `githubId`             | *string*               | :heavy_check_mark:     | N/A                    |
| `githubAppName`        | *string*               | :heavy_minus_sign:     | N/A                    |
| `githubAppId`          | *number*               | :heavy_minus_sign:     | N/A                    |
| `githubClientId`       | *string*               | :heavy_minus_sign:     | N/A                    |
| `githubClientSecret`   | *string*               | :heavy_minus_sign:     | N/A                    |
| `githubInstallationId` | *string*               | :heavy_minus_sign:     | N/A                    |
| `githubPrivateKey`     | *string*               | :heavy_minus_sign:     | N/A                    |
| `githubWebhookSecret`  | *string*               | :heavy_minus_sign:     | N/A                    |
| `gitProviderId`        | *string*               | :heavy_check_mark:     | N/A                    |
| `name`                 | *string*               | :heavy_check_mark:     | N/A                    |