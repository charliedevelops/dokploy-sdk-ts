# GitlabCreateRequest

## Example Usage

```typescript
import { GitlabCreateRequest } from "dokploy-sdk/models/operations";

let value: GitlabCreateRequest = {
  gitlabUrl: "https://weird-cash.biz/",
  authId: "<id>",
  name: "<value>",
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `gitlabId`         | *string*           | :heavy_minus_sign: | N/A                |
| `gitlabUrl`        | *string*           | :heavy_check_mark: | N/A                |
| `applicationId`    | *string*           | :heavy_minus_sign: | N/A                |
| `redirectUri`      | *string*           | :heavy_minus_sign: | N/A                |
| `secret`           | *string*           | :heavy_minus_sign: | N/A                |
| `accessToken`      | *string*           | :heavy_minus_sign: | N/A                |
| `refreshToken`     | *string*           | :heavy_minus_sign: | N/A                |
| `groupName`        | *string*           | :heavy_minus_sign: | N/A                |
| `expiresAt`        | *number*           | :heavy_minus_sign: | N/A                |
| `gitProviderId`    | *string*           | :heavy_minus_sign: | N/A                |
| `authId`           | *string*           | :heavy_check_mark: | N/A                |
| `name`             | *string*           | :heavy_check_mark: | N/A                |