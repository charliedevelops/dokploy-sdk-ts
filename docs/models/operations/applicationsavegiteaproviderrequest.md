# ApplicationSaveGiteaProviderRequest

## Example Usage

```typescript
import { ApplicationSaveGiteaProviderRequest } from "dokploy-sdk/models/operations";

let value: ApplicationSaveGiteaProviderRequest = {
  applicationId: "<id>",
  enableSubmodules: false,
  giteaBranch: "<value>",
  giteaBuildPath: "<value>",
  giteaId: "<id>",
  giteaOwner: null,
  giteaRepository: null,
};
```

## Fields

| Field              | Type               | Required           | Description        |
| ------------------ | ------------------ | ------------------ | ------------------ |
| `applicationId`    | *string*           | :heavy_check_mark: | N/A                |
| `enableSubmodules` | *boolean*          | :heavy_check_mark: | N/A                |
| `giteaBranch`      | *string*           | :heavy_check_mark: | N/A                |
| `giteaBuildPath`   | *string*           | :heavy_check_mark: | N/A                |
| `giteaId`          | *string*           | :heavy_check_mark: | N/A                |
| `giteaOwner`       | *string*           | :heavy_check_mark: | N/A                |
| `giteaRepository`  | *string*           | :heavy_check_mark: | N/A                |
| `watchPaths`       | *string*[]         | :heavy_minus_sign: | N/A                |