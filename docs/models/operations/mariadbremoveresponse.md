# MariadbRemoveResponse


## Supported Types

### `operations.MariadbRemoveResponseBody`

```typescript
const value: operations.MariadbRemoveResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "like once fussy an psst aboard surface eek",
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
  cpuLimit: null,
  externalPort: 534.94,
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 7793.22,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 5872.78,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: [],
  replicas: 8097.94,
  createdAt: "1729382718431",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "showy wound knavishly gratefully manipulate miserable agreement unto sans",
    createdAt: "1711395483111",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "spook whenever soup airbus zealous for deduct amid",
      createdAt: "1712617458655",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "file",
      hostPath: "<value>",
      volumeName: null,
      filePath: "/System/ack_rare_which.opus",
      content: "<value>",
      serviceType: "redis",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: null,
      redisId: "<id>",
      composeId: "<id>",
    },
  ],
  server: {
    serverId: "<id>",
    name: "<value>",
    description:
      "helplessly glass petty tenderly book unlike nor where showy now",
    ipAddress: "105.35.32.70",
    port: 7292.08,
    username: "Karli_Thiel",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1707525257665",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {},
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

