# GitlabUpdateRequest

## Example Usage

```typescript
import { GitlabUpdateRequest } from "dokploy-sdk/models/operations";

let value: GitlabUpdateRequest = {
  gitlabId: "<id>",
  gitlabUrl: "https://motionless-provider.biz",
  gitProviderId: "<id>",
  name: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `gitlabId`         | *string*           | :heavy_check_mark: | N/A                |
| `gitlabUrl`        | *string*           | :heavy_check_mark: | N/A                |
| `applicationId`    | *string*           | :heavy_minus_sign: | N/A                |
| `redirectUri`      | *string*           | :heavy_minus_sign: | N/A                |
| `secret`           | *string*           | :heavy_minus_sign: | N/A                |
| `accessToken`      | *string*           | :heavy_minus_sign: | N/A                |
| `refreshToken`     | *string*           | :heavy_minus_sign: | N/A                |
| `groupName`        | *string*           | :heavy_minus_sign: | N/A                |
| `expiresAt`        | *number*           | :heavy_minus_sign: | N/A                |
| `gitProviderId`    | *string*           | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |