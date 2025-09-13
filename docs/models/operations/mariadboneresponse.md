# MariadbOneResponse


## Supported Types

### `operations.MariadbOneResponseBody`

```typescript
const value: operations.MariadbOneResponseBody = {
  mariadbId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "shyly repossess who",
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
    parallelism: 6910.11,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 2171.56,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: null,
  networkSwarm: null,
  replicas: 4463.62,
  createdAt: "1711952973984",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "furthermore questionable rout whirlwind",
    createdAt: "1708965231542",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "boohoo meh so round lumpy nor unimportant",
      createdAt: "1725568589968",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "deceivingly by barring after swat modulo harp through",
    ipAddress: "93.88.120.190",
    port: 313.14,
    username: "Kamren63",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1727830605032",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: null,
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
      serviceName: "<value>",
      destinationId: "<id>",
      keepLatestCount: 6533.64,
      backupType: "database",
      databaseType: "mariadb",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mysqlId: "<id>",
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

