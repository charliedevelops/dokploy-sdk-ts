# PostgresStopResponse


## Supported Types

### `operations.PostgresStopResponseBody`

```typescript
const value: operations.PostgresStopResponseBody = {
  postgresId: "<id>",
  name: "<value>",
  appName: "<value>",
  databaseName: "<value>",
  databaseUser: "<value>",
  databasePassword: "<value>",
  description: null,
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  externalPort: 483.68,
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 3110.5,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 4890.7,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: {},
  networkSwarm: null,
  replicas: 4046.3,
  createdAt: "1724083716148",
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "so curry softly braid ick briskly wafer guilt",
    createdAt: "1712967784452",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "duh so now alongside",
      createdAt: "1719356730252",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  mounts: [
    {
      mountId: "<id>",
      type: "bind",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/usr/onto.xlw",
      content: "<value>",
      serviceType: "mariadb",
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
      "coaxingly engage converse anesthetize fat lest bah hm elegantly rundown",
    ipAddress: "f3ff:eccc:76bd:b98f:8ac1:2cbf:32a3:bf38",
    port: 8223.18,
    username: "Berniece.McClure-Bartell",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1729675297937",
    organizationId: "<id>",
    serverStatus: "active",
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

