# MariadbStopResponse


## Supported Types

### `operations.MariadbStopResponseBody`

```typescript
const value: operations.MariadbStopResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "commodity astride unit",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: null,
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 31.05,
    order: "<value>",
  },
  rollbackConfigSwarm: null,
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
  },
  networkSwarm: [],
  replicas: 5995.09,
  createdAt: "1719311180758",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "kindly drat unhappy rapid",
    createdAt: "1716339039813",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "elver mmm potable geez instead ugh snoop",
      createdAt: "1726446634911",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "devise hefty wherever unless pace than scenario whether",
    ipAddress: "107.105.87.235",
    port: 244.87,
    username: "Nels18",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1717512788681",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {
      "key": "<value>",
      "key1": "<value>",
    },
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

