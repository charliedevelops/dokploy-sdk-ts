# Github
(*github*)

## Overview

### Available Operations

* [githubOne](#githubone)
* [githubGetGithubRepositories](#githubgetgithubrepositories)
* [githubGetGithubBranches](#githubgetgithubbranches)
* [githubGithubProviders](#githubgithubproviders)
* [githubTestConnection](#githubtestconnection)
* [githubUpdate](#githubupdate)

## githubOne

### Example Usage

<!-- UsageSnippet language="typescript" operationID="github-one" method="get" path="/github.one" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.github.githubOne({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    githubId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { githubGithubOne } from "dokploy-sdk/funcs/githubGithubOne.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await githubGithubOne(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    githubId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("githubGithubOne failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.GithubOneRequest](../../models/operations/githubonerequest.md)                                                                                                     | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.GithubOneSecurity](../../models/operations/githubonesecurity.md)                                                                                                   | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.GithubOneResponse](../../models/operations/githuboneresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## githubGetGithubRepositories

### Example Usage

<!-- UsageSnippet language="typescript" operationID="github-getGithubRepositories" method="get" path="/github.getGithubRepositories" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.github.githubGetGithubRepositories({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    githubId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { githubGithubGetGithubRepositories } from "dokploy-sdk/funcs/githubGithubGetGithubRepositories.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await githubGithubGetGithubRepositories(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    githubId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("githubGithubGetGithubRepositories failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.GithubGetGithubRepositoriesRequest](../../models/operations/githubgetgithubrepositoriesrequest.md)                                                                 | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.GithubGetGithubRepositoriesSecurity](../../models/operations/githubgetgithubrepositoriessecurity.md)                                                               | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## githubGetGithubBranches

### Example Usage

<!-- UsageSnippet language="typescript" operationID="github-getGithubBranches" method="get" path="/github.getGithubBranches" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.github.githubGetGithubBranches({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    repo: "<value>",
    owner: "<value>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { githubGithubGetGithubBranches } from "dokploy-sdk/funcs/githubGithubGetGithubBranches.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await githubGithubGetGithubBranches(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    repo: "<value>",
    owner: "<value>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("githubGithubGetGithubBranches failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.GithubGetGithubBranchesRequest](../../models/operations/githubgetgithubbranchesrequest.md)                                                                         | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.GithubGetGithubBranchesSecurity](../../models/operations/githubgetgithubbranchessecurity.md)                                                                       | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## githubGithubProviders

### Example Usage

<!-- UsageSnippet language="typescript" operationID="github-githubProviders" method="get" path="/github.githubProviders" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.github.githubGithubProviders({
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
import { githubGithubGithubProviders } from "dokploy-sdk/funcs/githubGithubGithubProviders.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await githubGithubGithubProviders(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("githubGithubGithubProviders failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `security`                                                                                                                                                                     | [operations.GithubGithubProvidersSecurity](../../models/operations/githubgithubproviderssecurity.md)                                                                           | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.GithubGithubProvidersResponse](../../models/operations/githubgithubprovidersresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## githubTestConnection

### Example Usage

<!-- UsageSnippet language="typescript" operationID="github-testConnection" method="post" path="/github.testConnection" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.github.githubTestConnection({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    githubId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { githubGithubTestConnection } from "dokploy-sdk/funcs/githubGithubTestConnection.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await githubGithubTestConnection(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    githubId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("githubGithubTestConnection failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.GithubTestConnectionRequest](../../models/operations/githubtestconnectionrequest.md)                                                                               | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.GithubTestConnectionSecurity](../../models/operations/githubtestconnectionsecurity.md)                                                                             | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.GithubTestConnectionResponse](../../models/operations/githubtestconnectionresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## githubUpdate

### Example Usage

<!-- UsageSnippet language="typescript" operationID="github-update" method="post" path="/github.update" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.github.githubUpdate({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    githubId: "<id>",
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
import { githubGithubUpdate } from "dokploy-sdk/funcs/githubGithubUpdate.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await githubGithubUpdate(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    githubId: "<id>",
    gitProviderId: "<id>",
    name: "<value>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("githubGithubUpdate failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.GithubUpdateRequest](../../models/operations/githubupdaterequest.md)                                                                                               | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.GithubUpdateSecurity](../../models/operations/githubupdatesecurity.md)                                                                                             | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.GithubUpdateResponse](../../models/operations/githubupdateresponse.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |