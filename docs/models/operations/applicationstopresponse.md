# ApplicationStopResponse


## Supported Types

### `operations.ApplicationStopResponseBody`

```typescript
const value: operations.ApplicationStopResponseBody = {
  bitbucket: {
    appPassword: "<value>",
    bitbucketId: "<id>",
    bitbucketUsername: "<value>",
    bitbucketWorkspaceName: "<value>",
    gitProviderId: "<id>",
  },
  deployments: [
    {
      applicationId: null,
      backupId: "<id>",
      composeId: "<id>",
      createdAt: "1723878221457",
      deploymentId: "<id>",
      description: "gosh gadzooks than nor hmph whoever whose as a unless",
      errorMessage: "<value>",
      finishedAt: "<value>",
      isPreviewDeployment: false,
      logPath: "<value>",
      pid: "<id>",
      previewDeploymentId: "<id>",
      rollbackId: "<id>",
      scheduleId: "<id>",
      serverId: "<id>",
      startedAt: "<value>",
      status: "running",
      title: "<value>",
      volumeBackupId: "<id>",
    },
  ],
  domains: [],
  environment: {
    createdAt: "1719984209438",
    description: "long but amount acidly oof empty underneath beep round aha",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1730454078929",
      description: "fuss nervously rich uh-huh",
      env: "<value>",
      name: "<value>",
      organizationId: "<id>",
      projectId: "<id>",
    },
    projectId: "<id>",
  },
  environmentId: "<id>",
  gitea: {
    accessToken: "<value>",
    clientId: "<id>",
    clientSecret: "<value>",
    expiresAt: 5032.98,
    gitProviderId: "<id>",
    giteaId: "<id>",
    giteaUrl: "https://smug-gray.net",
    lastAuthenticatedAt: 1508.36,
    redirectUri: "https://hefty-breastplate.org",
    refreshToken: "<value>",
    scopes: "<value>",
  },
  github: null,
  gitlab: {
    accessToken: "<value>",
    applicationId: "<id>",
    expiresAt: 8539.48,
    gitProviderId: "<id>",
    gitlabId: "<id>",
    gitlabUrl: "https://negligible-electronics.net",
    groupName: "<value>",
    redirectUri: "https://fearless-corporation.name",
    refreshToken: null,
    secret: "<value>",
  },
  mounts: [
    {
      applicationId: "<id>",
      composeId: "<id>",
      content: "<value>",
      filePath: "/selinux/fray_that_comparison.list",
      hostPath: "<value>",
      mariadbId: "<id>",
      mongoId: "<id>",
      mountId: "<id>",
      mountPath: "<value>",
      mysqlId: "<id>",
      postgresId: "<id>",
      redisId: "<id>",
      serviceType: "redis",
      type: "file",
      volumeName: null,
    },
  ],
  name: "<value>",
  ports: [
    {
      applicationId: "<id>",
      portId: "<id>",
      protocol: "udp",
      publishMode: "ingress",
      publishedPort: 2013.96,
      targetPort: 5916.58,
    },
  ],
  previewDeployments: [
    {
      appName: "<value>",
      applicationId: "<id>",
      branch: "<value>",
      createdAt: "1708636404915",
      domainId: "<id>",
      expiresAt: "1749323109681",
      previewDeploymentId: "<id>",
      previewStatus: "error",
      pullRequestCommentId: "<id>",
      pullRequestId: "<id>",
      pullRequestNumber: "<value>",
      pullRequestTitle: "<value>",
      pullRequestURL: "https://deserted-obesity.name",
    },
  ],
  redirects: [],
  registry: {
    createdAt: "1708673929172",
    imagePrefix: "<value>",
    organizationId: "<id>",
    password: "lGhpZnJpaZgbIUA",
    registryId: "<id>",
    registryName: "<value>",
    registryType: "cloud",
    registryUrl: "https://intent-doing.info",
    username: "Warren.Bashirian87",
  },
  security: [
    {
      applicationId: "<id>",
      createdAt: "1731674517472",
      password: "e1RS730cZJjdWa7",
      securityId: "<id>",
      username: "Cleta_Klocko",
    },
  ],
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1728417310124",
    description: "meh kick fragrant elver acidic hard-to-find impanel subsidy",
    enableDockerCleanup: true,
    ipAddress: "17.13.40.81",
    metricsConfig: {},
    name: "<value>",
    organizationId: "<id>",
    port: 2089.9,
    serverId: "<id>",
    serverStatus: "inactive",
    sshKeyId: "<id>",
    username: "Wilma63",
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

