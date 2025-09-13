# MariadbDeployResponse


## Supported Types

### `operations.MariadbDeployResponseBody`

```typescript
const value: operations.MariadbDeployResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "house why closely out if ack",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: null,
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 3925.19,
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 5377.72,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 8194.78,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 1568.18,
  createdAt: "1731063207077",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "within precedent usually times complicated furthermore bakeware markup",
    createdAt: "1732027254082",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "deduct guzzle while homely up optimistically instead huzzah",
      createdAt: "1723177725048",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "sardonic morbidity better",
    ipAddress: "252.220.254.88",
    port: 9463.94,
    username: "Mallory.Koepp48",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1704892633937",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
      "<value 3>",
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

