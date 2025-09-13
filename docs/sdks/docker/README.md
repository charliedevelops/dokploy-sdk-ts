# Docker
(*docker*)

## Overview

### Available Operations

* [dockerGetContainers](#dockergetcontainers)
* [dockerRestartContainer](#dockerrestartcontainer)
* [dockerGetConfig](#dockergetconfig)
* [dockerGetContainersByAppNameMatch](#dockergetcontainersbyappnamematch)
* [dockerGetContainersByAppLabel](#dockergetcontainersbyapplabel)
* [dockerGetStackContainersByAppName](#dockergetstackcontainersbyappname)
* [dockerGetServiceContainersByAppName](#dockergetservicecontainersbyappname)

## dockerGetContainers

### Example Usage

<!-- UsageSnippet language="typescript" operationID="docker-getContainers" method="get" path="/docker.getContainers" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.docker.dockerGetContainers({
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
import { dockerDockerGetContainers } from "dokploy-sdk/funcs/dockerDockerGetContainers.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await dockerDockerGetContainers(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("dockerDockerGetContainers failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.DockerGetContainersRequest](../../models/operations/dockergetcontainersrequest.md)                                                                                 | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.DockerGetContainersSecurity](../../models/operations/dockergetcontainerssecurity.md)                                                                               | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## dockerRestartContainer

### Example Usage

<!-- UsageSnippet language="typescript" operationID="docker-restartContainer" method="post" path="/docker.restartContainer" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.docker.dockerRestartContainer({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    containerId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { dockerDockerRestartContainer } from "dokploy-sdk/funcs/dockerDockerRestartContainer.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await dockerDockerRestartContainer(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    containerId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("dockerDockerRestartContainer failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.DockerRestartContainerRequest](../../models/operations/dockerrestartcontainerrequest.md)                                                                           | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.DockerRestartContainerSecurity](../../models/operations/dockerrestartcontainersecurity.md)                                                                         | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## dockerGetConfig

### Example Usage

<!-- UsageSnippet language="typescript" operationID="docker-getConfig" method="get" path="/docker.getConfig" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.docker.dockerGetConfig({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    containerId: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { dockerDockerGetConfig } from "dokploy-sdk/funcs/dockerDockerGetConfig.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await dockerDockerGetConfig(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    containerId: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("dockerDockerGetConfig failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.DockerGetConfigRequest](../../models/operations/dockergetconfigrequest.md)                                                                                         | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.DockerGetConfigSecurity](../../models/operations/dockergetconfigsecurity.md)                                                                                       | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## dockerGetContainersByAppNameMatch

### Example Usage

<!-- UsageSnippet language="typescript" operationID="docker-getContainersByAppNameMatch" method="get" path="/docker.getContainersByAppNameMatch" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.docker.dockerGetContainersByAppNameMatch({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    appName: "<value>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { dockerDockerGetContainersByAppNameMatch } from "dokploy-sdk/funcs/dockerDockerGetContainersByAppNameMatch.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await dockerDockerGetContainersByAppNameMatch(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    appName: "<value>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("dockerDockerGetContainersByAppNameMatch failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.DockerGetContainersByAppNameMatchRequest](../../models/operations/dockergetcontainersbyappnamematchrequest.md)                                                     | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.DockerGetContainersByAppNameMatchSecurity](../../models/operations/dockergetcontainersbyappnamematchsecurity.md)                                                   | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## dockerGetContainersByAppLabel

### Example Usage

<!-- UsageSnippet language="typescript" operationID="docker-getContainersByAppLabel" method="get" path="/docker.getContainersByAppLabel" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.docker.dockerGetContainersByAppLabel({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    appName: "<value>",
    type: "standalone",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { dockerDockerGetContainersByAppLabel } from "dokploy-sdk/funcs/dockerDockerGetContainersByAppLabel.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await dockerDockerGetContainersByAppLabel(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    appName: "<value>",
    type: "standalone",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("dockerDockerGetContainersByAppLabel failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.DockerGetContainersByAppLabelRequest](../../models/operations/dockergetcontainersbyapplabelrequest.md)                                                             | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.DockerGetContainersByAppLabelSecurity](../../models/operations/dockergetcontainersbyapplabelsecurity.md)                                                           | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## dockerGetStackContainersByAppName

### Example Usage

<!-- UsageSnippet language="typescript" operationID="docker-getStackContainersByAppName" method="get" path="/docker.getStackContainersByAppName" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.docker.dockerGetStackContainersByAppName({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    appName: "<value>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { dockerDockerGetStackContainersByAppName } from "dokploy-sdk/funcs/dockerDockerGetStackContainersByAppName.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await dockerDockerGetStackContainersByAppName(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    appName: "<value>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("dockerDockerGetStackContainersByAppName failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.DockerGetStackContainersByAppNameRequest](../../models/operations/dockergetstackcontainersbyappnamerequest.md)                                                     | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.DockerGetStackContainersByAppNameSecurity](../../models/operations/dockergetstackcontainersbyappnamesecurity.md)                                                   | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |

## dockerGetServiceContainersByAppName

### Example Usage

<!-- UsageSnippet language="typescript" operationID="docker-getServiceContainersByAppName" method="get" path="/docker.getServiceContainersByAppName" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.docker.dockerGetServiceContainersByAppName({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    appName: "<value>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { dockerDockerGetServiceContainersByAppName } from "dokploy-sdk/funcs/dockerDockerGetServiceContainersByAppName.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await dockerDockerGetServiceContainersByAppName(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    appName: "<value>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("dockerDockerGetServiceContainersByAppName failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.DockerGetServiceContainersByAppNameRequest](../../models/operations/dockergetservicecontainersbyappnamerequest.md)                                                 | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.DockerGetServiceContainersByAppNameSecurity](../../models/operations/dockergetservicecontainersbyappnamesecurity.md)                                               | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |