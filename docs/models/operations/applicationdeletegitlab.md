# ApplicationDeleteGitlab

## Example Usage

```typescript
import { ApplicationDeleteGitlab } from "dokploy-sdk/models/operations";

let value: ApplicationDeleteGitlab = {
  gitlabId: "<id>",
  gitlabUrl: "https://pretty-appliance.org",
  applicationId: "<id>",
  redirectUri: "https://sudden-inspection.com/",
  secret: "<value>",
  accessToken: "<value>",
  refreshToken: null,
  groupName: "<value>",
  expiresAt: 8915.91,
  gitProviderId: "<id>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `gitlabId`         | *string*           | :heavy_check_mark: | N/A                |
| `gitlabUrl`        | *string*           | :heavy_check_mark: | N/A                |
| `applicationId`    | *string*           | :heavy_check_mark: | N/A                |
| `redirectUri`      | *string*           | :heavy_check_mark: | N/A                |
| `secret`           | *string*           | :heavy_check_mark: | N/A                |
| `accessToken`      | *string*           | :heavy_check_mark: | N/A                |
| `refreshToken`     | *string*           | :heavy_check_mark: | N/A                |
| `groupName`        | *string*           | :heavy_check_mark: | N/A                |
| `expiresAt`        | *number*           | :heavy_check_mark: | N/A                |
| `gitProviderId`    | *string*           | :heavy_check_mark: | N/A                |