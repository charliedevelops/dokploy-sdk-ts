# ApplicationSaveBuildTypeRequest

## Example Usage

```typescript
import { ApplicationSaveBuildTypeRequest } from "dokploy-sdk/models/operations";

let value: ApplicationSaveBuildTypeRequest = {
  applicationId: "<id>",
  buildType: "static",
  dockerContextPath: "<value>",
  dockerBuildStage: "<value>",
};
```

## Fields

| Field                                                                                                        | Type                                                                                                         | Required                                                                                                     | Description                                                                                                  |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `applicationId`                                                                                              | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `buildType`                                                                                                  | [operations.ApplicationSaveBuildTypeBuildType](../../models/operations/applicationsavebuildtypebuildtype.md) | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `dockerfile`                                                                                                 | *string*                                                                                                     | :heavy_minus_sign:                                                                                           | N/A                                                                                                          |
| `dockerContextPath`                                                                                          | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `dockerBuildStage`                                                                                           | *string*                                                                                                     | :heavy_check_mark:                                                                                           | N/A                                                                                                          |
| `herokuVersion`                                                                                              | *string*                                                                                                     | :heavy_minus_sign:                                                                                           | N/A                                                                                                          |
| `railpackVersion`                                                                                            | *string*                                                                                                     | :heavy_minus_sign:                                                                                           | N/A                                                                                                          |
| `publishDirectory`                                                                                           | *string*                                                                                                     | :heavy_minus_sign:                                                                                           | N/A                                                                                                          |
| `isStaticSpa`                                                                                                | *boolean*                                                                                                    | :heavy_minus_sign:                                                                                           | N/A                                                                                                          |