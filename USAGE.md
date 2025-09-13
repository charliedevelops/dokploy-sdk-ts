<!-- Start SDK Example Usage [usage] -->
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
<!-- End SDK Example Usage [usage] -->