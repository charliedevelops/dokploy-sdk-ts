# Admin
(*admin*)

## Overview

### Available Operations

* [adminSetupMonitoring](#adminsetupmonitoring)

## adminSetupMonitoring

### Example Usage

<!-- UsageSnippet language="typescript" operationID="admin-setupMonitoring" method="post" path="/admin.setupMonitoring" -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy();

async function run() {
  const result = await dokploy.admin.adminSetupMonitoring({
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    metricsConfig: {
      server: {
        refreshRate: 4397.9,
        port: 8537.41,
        token: "<value>",
        urlCallback: "https://majestic-scratch.org",
        retentionDays: 6999.95,
        cronJob: "<value>",
        thresholds: {
          cpu: 5497.84,
          memory: 6419.22,
        },
      },
      containers: {
        refreshRate: 7401.48,
        services: {},
      },
    },
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DokployCore } from "dokploy-sdk/core.js";
import { adminAdminSetupMonitoring } from "dokploy-sdk/funcs/adminAdminSetupMonitoring.js";

// Use `DokployCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const dokploy = new DokployCore();

async function run() {
  const res = await adminAdminSetupMonitoring(dokploy, {
    authorization: process.env["DOKPLOY_AUTHORIZATION"] ?? "",
  }, {
    metricsConfig: {
      server: {
        refreshRate: 4397.9,
        port: 8537.41,
        token: "<value>",
        urlCallback: "https://majestic-scratch.org",
        retentionDays: 6999.95,
        cronJob: "<value>",
        thresholds: {
          cpu: 5497.84,
          memory: 6419.22,
        },
      },
      containers: {
        refreshRate: 7401.48,
        services: {},
      },
    },
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("adminAdminSetupMonitoring failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.AdminSetupMonitoringRequest](../../models/operations/adminsetupmonitoringrequest.md)                                                                               | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `security`                                                                                                                                                                     | [operations.AdminSetupMonitoringSecurity](../../models/operations/adminsetupmonitoringsecurity.md)                                                                             | :heavy_check_mark:                                                                                                                                                             | The security requirements to use for the request.                                                                                                                              |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[models.ErrorT](../../models/errort.md)\>**

### Errors

| Error Type                 | Status Code                | Content Type               |
| -------------------------- | -------------------------- | -------------------------- |
| errors.DokployDefaultError | 4XX, 5XX                   | \*/\*                      |