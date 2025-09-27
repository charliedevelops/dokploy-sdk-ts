# MariadbDeployResponse


## Supported Types

### `operations.MariadbDeployResponseBody`

```typescript
const value: operations.MariadbDeployResponseBody = {
  appName: "<value>",
  applicationStatus: "idle",
  backups: [],
  command: "<value>",
  cpuLimit: "<value>",
  cpuReservation: "<value>",
  createdAt: "1713331361129",
  databaseName: "<value>",
  databasePassword: "<value>",
  databaseRootPassword: "<value>",
  databaseUser: "<value>",
  description: "along besides management fooey cease",
  dockerImage: "<value>",
  env: "<value>",
  environment: {
    createdAt: "1710520347234",
    description: "developing specific incidentally above er",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1726195672478",
      description: "hello institutionalize browse",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  externalPort: 6989.39,
  healthCheckSwarm: {},
  labelsSwarm: {
    "key": "<value>",
    "key1": "<value>",
    "key2": "<value>",
  },
  mariadbId: "<id>",
  memoryLimit: "<value>",
  memoryReservation: "<value>",
  modeSwarm: null,
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/var/useless.dump",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "postgres",
      type: "file",
      volumeName: "<value>",
    },
  ],
  name: "<value>",
  networkSwarm: [],
  placementSwarm: {},
  replicas: 3196.93,
  restartPolicySwarm: null,
  rollbackConfigSwarm: {
    order: "<value>",
    parallelism: 4550.87,
  },
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1730684156671",
    description: null,
    enableDockerCleanup: true,
    ipAddress: "d4ba:2e67:fbbf:82ad:0fcc:5ae8:b14f:cf7e",
    metricsConfig: [
      "<value 1>",
      "<value 2>",
    ],
    name: "<value>",
    organizationId: "<id>",
    port: 4608.94,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Caroline_Bailey",
  },
  serverId: "<id>",
  updateConfigSwarm: {
    order: "<value>",
    parallelism: 3265.8,
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

