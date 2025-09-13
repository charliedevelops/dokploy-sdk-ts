# MongoSaveExternalPortResponse


## Supported Types

### `operations.MongoSaveExternalPortResponseBody`

```typescript
const value: operations.MongoSaveExternalPortResponseBody = {
  mongoId: "<id>",
  name: "<value>",
  appName: "<value>",
  description: "sense for modulo scholarship",
  databaseUser: "<value>",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: null,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 1148.94,
  applicationStatus: "done",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 6930.95,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 9258.44,
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
  replicas: 5940.89,
  createdAt: "1704258420488",
  environmentId: "<id>",
  serverId: "<id>",
  replicaSets: false,
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "anenst ill overload source suspiciously appliance meatloaf loyally qua",
    createdAt: "1716137948019",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "fisherman given till tattered",
      createdAt: "1711813881104",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [],
  server: null,
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
      keepLatestCount: 3086.92,
      backupType: "compose",
      databaseType: "mariadb",
      composeId: "<id>",
      postgresId: "<id>",
      mariadbId: null,
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

