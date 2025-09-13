# MysqlSaveExternalPortResponse


## Supported Types

### `operations.MysqlSaveExternalPortResponseBody`

```typescript
const value: operations.MysqlSaveExternalPortResponseBody = {
  mysqlId: "<id>",
  name: "<value>",
  appName: "<value>",
  description:
    "covenant midst whoa cross physically naturally owlishly certify meh",
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
  externalPort: 2105.73,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 3055.41,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 739.59,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  networkSwarm: [],
  replicas: 3178.72,
  createdAt: "1716968843079",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: null,
    createdAt: "1719054654952",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "bad fat anenst diver showboat fooey across yowza internalise",
      createdAt: "1718950932828",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "file",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/etc/defaults/hmph.opus",
      content: "<value>",
      serviceType: "mongo",
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
    description: null,
    ipAddress: "78.24.180.222",
    port: 1273.67,
    username: "Lisette_Jenkins",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1734994155315",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {
      "key": "<value>",
    },
  },
  backups: [
    {
      backupId: "<id>",
      appName: "<value>",
      schedule: "<value>",
      enabled: true,
      database: "<value>",
      prefix: "<value>",
      serviceName: "<value>",
      destinationId: "<id>",
      keepLatestCount: 1797.02,
      backupType: "compose",
      databaseType: "mysql",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: "<id>",
      mongoId: "<id>",
      userId: null,
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

