# RedisRemoveResponse


## Supported Types

### `operations.RedisRemoveResponseBody`

```typescript
const value: operations.RedisRemoveResponseBody = {
  redisId: "<id>",
  name: "<value>",
  appName: "<value>",
  description:
    "phooey because wholly adventurously ready anxiously fatherly blah pasta",
  databasePassword: "<value>",
  dockerImage: "<value>",
  command: "<value>",
  env: "<value>",
  memoryReservation: "<value>",
  memoryLimit: "<value>",
  cpuReservation: "<value>",
  cpuLimit: "<value>",
  externalPort: 6207.21,
  createdAt: "1724345759673",
  applicationStatus: "error",
  healthCheckSwarm: {},
  restartPolicySwarm: {},
  placementSwarm: {},
  updateConfigSwarm: {
    parallelism: 8013,
    order: "<value>",
  },
  rollbackConfigSwarm: {
    parallelism: 6701.09,
    order: "<value>",
  },
  modeSwarm: {},
  labelsSwarm: null,
  networkSwarm: [],
  replicas: 5468.42,
  environmentId: "<id>",
  serverId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "numb translation psst except overspend cinch backburn where federate ha",
    createdAt: "1725177528397",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "viciously elegantly supposing boastfully bah knight atop",
      createdAt: "1716559476779",
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
      filePath: "/lost+found/yuck.mjs",
      content: "<value>",
      serviceType: "postgres",
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
    description: "puzzled pace great but jut fold deserted cop-out",
    ipAddress: "fa8f:230d:5e9e:d77e:ae72:3d2b:a71b:f5c7",
    port: 5322.41,
    username: "Jasper_Franecki57",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1708657769563",
    organizationId: "<id>",
    serverStatus: "inactive",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: "null",
  },
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

