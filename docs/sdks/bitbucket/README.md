# Bitbucket
(*bitbucket*)

## Overview

### Available Operations

* [bitbucketCreate](#bitbucketcreate)
* [bitbucketOne](#bitbucketone)
* [bitbucketBitbucketProviders](#bitbucketbitbucketproviders)
* [bitbucketGetBitbucketRepositories](#bitbucketgetbitbucketrepositories)
* [bitbucketGetBitbucketBranches](#bitbucketgetbitbucketbranches)
* [bitbucketTestConnection](#bitbuckettestconnection)
* [bitbucketUpdate](#bitbucketupdate)

## bitbucketCreate

### Example Usage

<!-- UsageSnippet language="typescript" operationID="bitbucket-create" method="post" path="/bitbucket.create" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.bitbucket.bitbucketCreate({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    authId: "<id>",
    name: "<value>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { bitbucketBitbucketCreate } from "dokploy-sdk/funcs/bitbucketBitbucketCreate.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await bitbucketBitbucketCreate(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    authId: "<id>",
    name: "<value>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("bitbucketBitbucketCreate failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.BitbucketCreateRequest](../../models/operations/bitbucketcreaterequest.md)                                                                                         | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.BitbucketCreateSecurity](../../models/operations/bitbucketcreatesecurity.md)                                                                                       | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## bitbucketOne

### Example Usage

<!-- UsageSnippet language="typescript" operationID="bitbucket-one" method="get" path="/bitbucket.one" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.bitbucket.bitbucketOne({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    bitbucketId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { bitbucketBitbucketOne } from "dokploy-sdk/funcs/bitbucketBitbucketOne.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await bitbucketBitbucketOne(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    bitbucketId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("bitbucketBitbucketOne failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.BitbucketOneRequest](../../models/operations/bitbucketonerequest.md)                                                                                               | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.BitbucketOneSecurity](../../models/operations/bitbucketonesecurity.md)                                                                                             | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.BitbucketOneResponse](../../models/operations/bitbucketoneresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## bitbucketBitbucketProviders

### Example Usage

<!-- UsageSnippet language="typescript" operationID="bitbucket-bitbucketProviders" method="get" path="/bitbucket.bitbucketProviders" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.bitbucket.bitbucketBitbucketProviders({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { bitbucketBitbucketBitbucketProviders } from "dokploy-sdk/funcs/bitbucketBitbucketBitbucketProviders.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await bitbucketBitbucketBitbucketProviders(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("bitbucketBitbucketBitbucketProviders failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `security`                                                                                                                                                                     | [operations.BitbucketBitbucketProvidersSecurity](../../models/operations/bitbucketbitbucketproviderssecurity.md)                                                               | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.BitbucketBitbucketProvidersResponse](../../models/operations/bitbucketbitbucketprovidersresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## bitbucketGetBitbucketRepositories

### Example Usage

<!-- UsageSnippet language="typescript" operationID="bitbucket-getBitbucketRepositories" method="get" path="/bitbucket.getBitbucketRepositories" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.bitbucket.bitbucketGetBitbucketRepositories({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    bitbucketId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { bitbucketBitbucketGetBitbucketRepositories } from "dokploy-sdk/funcs/bitbucketBitbucketGetBitbucketRepositories.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await bitbucketBitbucketGetBitbucketRepositories(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    bitbucketId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("bitbucketBitbucketGetBitbucketRepositories failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.BitbucketGetBitbucketRepositoriesRequest](../../models/operations/bitbucketgetbitbucketrepositoriesrequest.md)                                                     | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.BitbucketGetBitbucketRepositoriesSecurity](../../models/operations/bitbucketgetbitbucketrepositoriessecurity.md)                                                   | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## bitbucketGetBitbucketBranches

### Example Usage

<!-- UsageSnippet language="typescript" operationID="bitbucket-getBitbucketBranches" method="get" path="/bitbucket.getBitbucketBranches" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.bitbucket.bitbucketGetBitbucketBranches({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    owner: "<value>",
    repo: "<value>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { bitbucketBitbucketGetBitbucketBranches } from "dokploy-sdk/funcs/bitbucketBitbucketGetBitbucketBranches.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await bitbucketBitbucketGetBitbucketBranches(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    owner: "<value>",
    repo: "<value>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("bitbucketBitbucketGetBitbucketBranches failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.BitbucketGetBitbucketBranchesRequest](../../models/operations/bitbucketgetbitbucketbranchesrequest.md)                                                             | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.BitbucketGetBitbucketBranchesSecurity](../../models/operations/bitbucketgetbitbucketbranchessecurity.md)                                                           | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## bitbucketTestConnection

### Example Usage

<!-- UsageSnippet language="typescript" operationID="bitbucket-testConnection" method="post" path="/bitbucket.testConnection" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.bitbucket.bitbucketTestConnection({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    bitbucketId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { bitbucketBitbucketTestConnection } from "dokploy-sdk/funcs/bitbucketBitbucketTestConnection.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await bitbucketBitbucketTestConnection(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    bitbucketId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("bitbucketBitbucketTestConnection failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.BitbucketTestConnectionRequest](../../models/operations/bitbuckettestconnectionrequest.md)                                                                         | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.BitbucketTestConnectionSecurity](../../models/operations/bitbuckettestconnectionsecurity.md)                                                                       | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.BitbucketTestConnectionResponse](../../models/operations/bitbuckettestconnectionresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## bitbucketUpdate

### Example Usage

<!-- UsageSnippet language="typescript" operationID="bitbucket-update" method="post" path="/bitbucket.update" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.bitbucket.bitbucketUpdate({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    bitbucketId: "<id>",
    gitProviderId: "<id>",
    name: "<value>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { bitbucketBitbucketUpdate } from "dokploy-sdk/funcs/bitbucketBitbucketUpdate.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await bitbucketBitbucketUpdate(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    bitbucketId: "<id>",
    gitProviderId: "<id>",
    name: "<value>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("bitbucketBitbucketUpdate failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.BitbucketUpdateRequest](../../models/operations/bitbucketupdaterequest.md)                                                                                         | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.BitbucketUpdateSecurity](../../models/operations/bitbucketupdatesecurity.md)                                                                                       | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.BitbucketUpdateResponse](../../models/operations/bitbucketupdateresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |