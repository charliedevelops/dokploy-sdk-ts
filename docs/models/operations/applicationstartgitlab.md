# ApplicationStartGitlab

## Example Usage

```typescript
import { ApplicationStartGitlab } from "dokploy-sdk/models/operations";

let value: ApplicationStartGitlab = {
  gitlabId: "<id>",
  gitlabUrl: "https://candid-representation.biz",
  applicationId: "<id>",
  redirectUri: "https://timely-pick.net",
  secret: "<value>",
  accessToken: "<value>",
  refreshToken: "<value>",
  groupName: null,
  expiresAt: 8631.71,
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