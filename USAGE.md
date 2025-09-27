<!-- Start SDK Example Usage [usage] -->
```typescript
import { Dokploy } from "dokploy-sdk";

const dokploy = new Dokploy({
  apiKeyAuth: process.env["DOKPLOY_API_KEY_AUTH"] ?? "",
});

async function run() {
  const result = await dokploy.admin.setupMonitoring({
    metricsConfig: {
      containers: {
        refreshRate: 7401.48,
        services: {},
      },
      server: {
        cronJob: "<value>",
        port: 8537.41,
        refreshRate: 4397.9,
        retentionDays: 6999.95,
        thresholds: {
          cpu: 5497.84,
          memory: 6419.22,
        },
        token: "<value>",
        urlCallback: "https://majestic-scratch.org",
      },
    },
  });

  console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->