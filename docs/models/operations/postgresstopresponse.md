# PostgresStopResponse


## Supported Types

### `operations.PostgresStopResponseBody`

```typescript
const value: operations.PostgresStopResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1705678954173",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseUser: "<value>",
  description: "general kiddingly torn minus quicker notwithstanding lox since",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1709899479925",
    description: null,
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1707969860361",
      description:
        "phooey bolster deer oof clone merrily ugh silky draw overplay",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: null,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
  },
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: null,
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/usr/libexec/singing_hunger.rar",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "compose",
      type: "file",
      volumeName: null,
    },
  ],
  name: "<value>",
  networkSwarm: [
    {},
  ],
  placementSwarm: {},
  postgresId: "<id>",
  replicas: 9182.93,
  restartPolicySwarm: {},
  rollbackConfigSwarm: null,
  server: null,
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 8816.22,
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

