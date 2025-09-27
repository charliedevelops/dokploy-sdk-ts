# PostgresDeployResponse


## Supported Types

### `operations.PostgresDeployResponseBody`

```typescript
const value: operations.PostgresDeployResponseBody = {
  appName: "<value>",
  applicationStatus: "running",
  backups: [
    {
      appName: "<value>",
      backupId: "<id>",
      backupType: "database",
      composeId: "<id>",
      database: "<value>",
      databaseType: "mysql",
      destinationId: "<id>",
      enabled: true,
      keepLatestCount: 5679.37,
      mariadbId: "<id>",
      mongoId: "<id>",
      mysqlId: "<id>",
      postgresId: null,
      prefix: "<value>",
      schedule: "<value>",
      serviceName: "<value>",
      userId: "<id>",
    },
  ],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1730011592067",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "for worth boohoo",
  dockerImage: "<value>",
  env: null,
  environment: {
    createdAt: "1706562213350",
    description: "as considerate ack",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1721924550637",
      description:
        "instantly reboot joyous opposite nor rural inasmuch comestible wherever bah",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 9351.3,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: {},
  mounts: [],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: null,
  postgresId: "<id>",
  replicas: 4797.58,
  restartPolicySwarm: {},
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 7110.21,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1721471978556",
    description: "honestly powerful geez shark toothbrush",
    enableDockerCleanup: true,
    ipAddress: "9241:64e3:7a2a:b4ba:0adb:eac6:3bbb:0e3d",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
      "<value 3>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 712.65,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Hyman75",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 4468.67,
  },
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  code: "<value>",
  message: "<value>",
};
```

