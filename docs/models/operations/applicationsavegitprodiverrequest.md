# ApplicationSaveGitProdiverRequest

## Example Usage

```typescript
import { ApplicationSaveGitProdiverRequest } from "dokploy-sdk/models/operations";

let value: ApplicationSaveGitProdiverRequest = {
  applicationId: "<id>",
  enableSubmodules: true,
};
```

## Fields

| Field                | Type                 | Required             | Description          |
| -------------------- | -------------------- | -------------------- | -------------------- |
| `customGitBranch`    | *string*             | :heavy_minus_sign:   | N/A                  |
| `applicationId`      | *string*             | :heavy_check_mark:   | N/A                  |
| `customGitBuildPath` | *string*             | :heavy_minus_sign:   | N/A                  |
| `customGitUrl`       | *string*             | :heavy_minus_sign:   | N/A                  |
| `watchPaths`         | *string*[]           | :heavy_minus_sign:   | N/A                  |
| `enableSubmodules`   | *boolean*            | :heavy_check_mark:   | N/A                  |
| `customGitSSHKeyId`  | *string*             | :heavy_minus_sign:   | N/A                  |