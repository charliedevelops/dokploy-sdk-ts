# PostgresDeployResponse


## Supported Types

### `operations.PostgresDeployResponseBody`

```typescript
const value: operations.PostgresDeployResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description:
    "midst shrilly barring lovingly yahoo bludgeon wonderfully sideboard",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: null,
  memoryLimit: "<value>",
  cpuReservation: null,
  cpuLimit: "<value>",
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 5541.39,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 7894.81,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: [],
  replicas: 604.49,
  createdAt: "1719283246632",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "optimal er fully phew interestingly meanwhile even phew",
    createdAt: "1719461551088",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "patiently that in phew drat until great gripping regular nor",
      createdAt: "1735025392039",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "inside saw gosh pish past fooey writhing",
    ipAddress: "110.100.41.238",
    port: 6540.94,
    username: "Betsy_Skiles9",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1731191954944",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
    ],
  },
  backups: [],
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

