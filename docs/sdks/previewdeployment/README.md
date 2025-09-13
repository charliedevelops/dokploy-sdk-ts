# PreviewDeployment
(*previewDeployment*)

## Overview

### Available Operations

* [previewDeploymentAll](#previewdeploymentall)
* [previewDeploymentDelete](#previewdeploymentdelete)
* [previewDeploymentOne](#previewdeploymentone)

## previewDeploymentAll

### Example Usage

<!-- UsageSnippet language="typescript" operationID="previewDeployment-all" method="get" path="/previewDeployment.all" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.previewDeployment.previewDeploymentAll({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    applicationId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { previewDeploymentPreviewDeploymentAll } from "dokploy-sdk/funcs/previewDeploymentPreviewDeploymentAll.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await previewDeploymentPreviewDeploymentAll(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    applicationId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("previewDeploymentPreviewDeploymentAll failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.PreviewDeploymentAllRequest](../../models/operations/previewdeploymentallrequest.md)                                                                               | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.PreviewDeploymentAllSecurity](../../models/operations/previewdeploymentallsecurity.md)                                                                             | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.PreviewDeploymentAllResponse](../../models/operations/previewdeploymentallresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## previewDeploymentDelete

### Example Usage

<!-- UsageSnippet language="typescript" operationID="previewDeployment-delete" method="post" path="/previewDeployment.delete" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.previewDeployment.previewDeploymentDelete({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    previewDeploymentId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { previewDeploymentPreviewDeploymentDelete } from "dokploy-sdk/funcs/previewDeploymentPreviewDeploymentDelete.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await previewDeploymentPreviewDeploymentDelete(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    previewDeploymentId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("previewDeploymentPreviewDeploymentDelete failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.PreviewDeploymentDeleteRequest](../../models/operations/previewdeploymentdeleterequest.md)                                                                         | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.PreviewDeploymentDeleteSecurity](../../models/operations/previewdeploymentdeletesecurity.md)                                                                       | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.PreviewDeploymentDeleteResponse](../../models/operations/previewdeploymentdeleteresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## previewDeploymentOne

### Example Usage

<!-- UsageSnippet language="typescript" operationID="previewDeployment-one" method="get" path="/previewDeployment.one" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.previewDeployment.previewDeploymentOne({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    previewDeploymentId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { previewDeploymentPreviewDeploymentOne } from "dokploy-sdk/funcs/previewDeploymentPreviewDeploymentOne.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await previewDeploymentPreviewDeploymentOne(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    previewDeploymentId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("previewDeploymentPreviewDeploymentOne failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.PreviewDeploymentOneRequest](../../models/operations/previewdeploymentonerequest.md)                                                                               | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.PreviewDeploymentOneSecurity](../../models/operations/previewdeploymentonesecurity.md)                                                                             | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.PreviewDeploymentOneResponse](../../models/operations/previewdeploymentoneresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |