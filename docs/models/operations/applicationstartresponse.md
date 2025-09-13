# ApplicationStartResponse


## Supported Types

### `operations.ApplicationStartResponseBody`

```typescript
const value: operations.ApplicationStartResponseBody = {
  name: "<value>",
  environmentId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "sleepy trial until sway maintainer until barring",
    createdAt: "1717643455195",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description: "tankful yahoo hence neck",
      createdAt: "1709110549258",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  domains: [],
  deployments: [
    {
      deploymentId: "<id>",
      title: "<value>",
      description: "venom youthfully critical other",
      status: null,
      logPath: "<value>",
      pid: "<id>",
      applicationId: null,
      composeId: "<id>",
      serverId: "<id>",
      isPreviewDeployment: true,
      previewDeploymentId: "<id>",
      createdAt: "1715560141517",
      startedAt: "<value>",
      finishedAt: "<value>",
      errorMessage: "<value>",
      scheduleId: "<id>",
      backupId: "<id>",
      rollbackId: "<id>",
      volumeBackupId: "<id>",
    },
  ],
  mounts: [
    {
      mountId: "<id>",
      type: "bind",
      hostPath: "<value>",
      volumeName: "<value>",
      filePath: "/etc/unaccountably.woff",
      content: "<value>",
      serviceType: "compose",
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
  redirects: [
    {
      redirectId: "<id>",
      regex: "<value>",
      replacement: "<value>",
      permanent: true,
      uniqueConfigKey: 5788.81,
      createdAt: "1707356094635",
      applicationId: "<id>",
    },
  ],
  security: [],
  ports: [
    {
      portId: "<id>",
      publishedPort: 153.4,
      publishMode: "ingress",
      targetPort: 824.02,
      protocol: "udp",
      applicationId: "<id>",
    },
  ],
  registry: {
    registryId: "<id>",
    registryName: "<value>",
    imagePrefix: "<value>",
    username: "Chyna_Kuvalis33",
    password: "fAF_RcxjvMV86g5",
    registryUrl: "https://unimportant-adviser.net",
    createdAt: "1729773724342",
    registryType: "selfHosted",
    organizationId: "<id>",
  },
  github: {
    githubId: "<id>",
    githubAppName: "<value>",
    githubAppId: 4821.58,
    githubClientId: "<id>",
    githubClientSecret: "<value>",
    githubInstallationId: "<id>",
    githubPrivateKey: "<value>",
    githubWebhookSecret: "<value>",
    gitProviderId: "<id>",
  },
  gitlab: {
    gitlabId: "<id>",
    gitlabUrl: "https://well-to-do-government.net/",
    applicationId: "<id>",
    redirectUri: "https://considerate-suitcase.name/",
    secret: "<value>",
    accessToken: "<value>",
    refreshToken: "<value>",
    groupName: "<value>",
    expiresAt: 2490.21,
    gitProviderId: "<id>",
  },
  bitbucket: {
    bitbucketId: "<id>",
    bitbucketUsername: "<value>",
    appPassword: "<value>",
    bitbucketWorkspaceName: "<value>",
    gitProviderId: "<id>",
  },
  gitea: {
    giteaId: "<id>",
    giteaUrl: "https://dim-mountain.biz/",
    redirectUri: "https://infinite-eternity.net",
    clientId: "<id>",
    clientSecret: "<value>",
    gitProviderId: "<id>",
    accessToken: "<value>",
    refreshToken: "<value>",
    expiresAt: 7320.27,
    scopes: "<value>",
    lastAuthenticatedAt: 7651.75,
  },
  server: {
    serverId: "<id>",
    name: "<value>",
    description: "upon meh fatal lumpy even into task joyously",
    ipAddress: "4bac:8a45:0320:26b9:e84a:6dbd:a73f:d771",
    port: 4401.19,
    username: "Russell.Runte",
    appName: "<value>",
    enableDockerCleanup: false,
    createdAt: "1717481954270",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: {
      "key": "<value>",
    },
  },
  previewDeployments: [
    {
      previewDeploymentId: "<id>",
      branch: "<value>",
      pullRequestId: "<id>",
      pullRequestNumber: "<value>",
      pullRequestURL: "https://magnificent-secret.net",
      pullRequestTitle: "<value>",
      pullRequestCommentId: "<id>",
      previewStatus: "done",
      appName: "<value>",
      applicationId: "<id>",
      domainId: "<id>",
      createdAt: "1704969568503",
      expiresAt: null,
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

