# ApplicationSaveGiteaProviderRequest

## Example Usage

```typescript
import { ApplicationSaveGiteaProviderRequest } from "dokploy-sdk/models/operations";

let value: ApplicationSaveGiteaProviderRequest = {
  applicationId: "<id>",
  giteaBranch: "<value>",
  giteaBuildPath: "<value>",
  giteaOwner: "<value>",
  giteaRepository: "<value>",
  giteaId: null,
  enableSubmodules: true,
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `applicationId`    | *string*           | :heavy_check_mark: | N/A                |
| `giteaBranch`      | *string*           | :heavy_check_mark: | N/A                |
| `giteaBuildPath`   | *string*           | :heavy_check_mark: | N/A                |
| `giteaOwner`       | *string*           | :heavy_check_mark: | N/A                |
| `giteaRepository`  | *string*           | :heavy_check_mark: | N/A                |
| `giteaId`          | *string*           | :heavy_check_mark: | N/A                |
| `watchPaths`       | *string*[]         | :heavy_minus_sign: | N/A                |
| `enableSubmodules` | *boolean*          | :heavy_check_mark: | N/A                |