# MysqlStopResponse


## Supported Types

### `operations.MysqlStopResponseBody`

```typescript
const value: operations.MysqlStopResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "hype between for hourly politely",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: null,
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 1912.25,
  applicationStatus: "running",
  healthCheckSwarm: {},
  restartPolicySwarm: null,
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 995.17,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 3039.41,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  networkSwarm: [
    {},
  ],
  replicas: 3452.66,
  createdAt: "1725061829504",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "for boom merge communicate",
    createdAt: "1733535465303",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "lawmaker since sandbar throughout however than excepting whenever although vanish",
      createdAt: "1710644887396",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "volume",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: null,
      content: "<value>",
      serviceType: "mariadb",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      redisId: "<id>",
      composeId: "<id>",
    },
  ],
  server: {
    serverId: "<id>",
    name: "<value>",
    description:
      "palate woot utilization westernize quantify scout scared untimely willfully rarely",
    ipAddress: "1a1c:ffd6:ed32:adc0:542e:7624:25b2:0caa",
    port: 6769.06,
    username: "Dax.West40",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1709568494706",
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
  backups: [
    {
      backupId: "<id>",
      appName: "<value>",
      schedule: "<value>",
      enabled: false,
      database: "<value>",
      prefix: "<value>",
      serviceName: null,
      destinationId: "<id>",
      keepLatestCount: 4765.36,
      backupType: "compose",
      databaseType: "mariadb",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: null,
      mongoId: "<id>",
      userId: "<id>",
    },
  ],
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

