# ApplicationOneResponse


## Supported Types

### `operations.ApplicationOneResponseBody`

```typescript
const value: operations.ApplicationOneResponseBody = {
  name: "<value>",
  environmentId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description:
      "inside near gah bathrobe hovercraft boo bungalow questioningly famously",
    createdAt: "1715740473391",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "bulky including expatiate train realistic physically coexist beyond greatly hmph",
      createdAt: "1734678614871",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  domains: [],
  deployments: [
    {
      deploymentId: "<id>",
      title: "<value>",
      description: "nicely aha bah impassioned from now",
      status: "done",
      logPath: "<value>",
      pid: "<id>",
      applicationId: "<id>",
      composeId: "<id>",
      serverId: "<id>",
      isPreviewDeployment: false,
      previewDeploymentId: "<id>",
      createdAt: "1707387343079",
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
      type: "file",
      hostPath: null,
      volumeName: "<value>",
      filePath: "/dev/wearily_when_till.rtf",
      content: "<value>",
      serviceType: "mongo",
      mountPath: "<value>",
      applicationId: "<id>",
      postgresId: "<id>",
      mariadbId: "<id>",
      mongoId: null,
      mysqlId: "<id>",
      redisId: "<id>",
      composeId: "<id>",
    },
  ],
  redirects: [],
  security: [],
  ports: [
    {
      portId: "<id>",
      publishedPort: 3618.65,
      publishMode: "host",
      targetPort: 8106.45,
      protocol: "tcp",
      applicationId: "<id>",
    },
  ],
  registry: {
    registryId: "<id>",
    registryName: "<value>",
    imagePrefix: null,
    username: "Joan99",
    password: "lHNg_Nz11f3S_2K",
    registryUrl: "https://wrathful-status.org",
    createdAt: "1708462558662",
    registryType: "cloud",
    organizationId: "<id>",
  },
  github: {
    githubId: "<id>",
    githubAppName: "<value>",
    githubAppId: null,
    githubClientId: "<id>",
    githubClientSecret: "<value>",
    githubInstallationId: null,
    githubPrivateKey: "<value>",
    githubWebhookSecret: "<value>",
    gitProviderId: "<id>",
  },
  gitlab: {
    gitlabId: "<id>",
    gitlabUrl: "https://buzzing-backburn.com",
    applicationId: "<id>",
    redirectUri: "https://clueless-fellow.name",
    secret: "<value>",
    accessToken: "<value>",
    refreshToken: "<value>",
    groupName: "<value>",
    expiresAt: 4269.36,
    gitProviderId: "<id>",
  },
  bitbucket: null,
  gitea: {
    giteaId: "<id>",
    giteaUrl: "https://rough-championship.org/",
    redirectUri: null,
    clientId: "<id>",
    clientSecret: null,
    gitProviderId: "<id>",
    accessToken: "<value>",
    refreshToken: "<value>",
    expiresAt: 2957.22,
    scopes: "<value>",
    lastAuthenticatedAt: 3343.96,
  },
  server: null,
  previewDeployments: [
    {
      previewDeploymentId: "<id>",
      branch: "<value>",
      pullRequestId: "<id>",
      pullRequestNumber: "<value>",
      pullRequestURL: "https://unused-ceramics.org/",
      pullRequestTitle: "<value>",
      pullRequestCommentId: "<id>",
      previewStatus: "idle",
      appName: "<value>",
      applicationId: "<id>",
      domainId: "<id>",
      createdAt: "1711942290070",
      expiresAt: "1763474622945",
    },
  ],
  hasGitProviderAccess: true,
  unauthorizedProvider: "github",
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

