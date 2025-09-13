# ApplicationStartResponse


## Supported Types

### `operations.ApplicationStartResponseBody`

```typescript
const value: operations.ApplicationStartResponseBody = {
  bitbucket: {
    appPassword: "<value>",
    bitbucketId: "<id>",
    bitbucketUsername: "<value>",
    bitbucketWorkspaceName: "<value>",
    gitProviderId: "<id>",
  },
  deployments: [
    {
      applicationId: "<id>",
      backupId: "<id>",
      composeId: "<id>",
      createdAt: "1727891952052",
      deploymentId: "<id>",
      description: null,
      errorMessage: "<value>",
      finishedAt: "<value>",
      isPreviewDeployment: true,
      logPath: "<value>",
      pid: "<id>",
      previewDeploymentId: "<id>",
      rollbackId: "<id>",
      scheduleId: "<id>",
      serverId: "<id>",
      startedAt: "<value>",
      status: "done",
      title: "<value>",
      volumeBackupId: "<id>",
    },
  ],
  domains: [],
  environment: {
    createdAt: "1717397140543",
    description: "into quinoa than these",
    env: "<value>",
    environmentId: "<id>",
    name: "<value>",
    project: {
      createdAt: "1732122037501",
      description: "untimely that zowie but",
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
    clientSecret: null,
    expiresAt: 7822.55,
    gitProviderId: "<id>",
    giteaId: "<id>",
    giteaUrl: "https://whimsical-tinderbox.com",
    lastAuthenticatedAt: 8235.55,
    redirectUri: "https://zealous-napkin.biz/",
    refreshToken: "<value>",
    scopes: "<value>",
  },
  github: {
    gitProviderId: "<id>",
    githubAppId: 1510.73,
    githubAppName: "<value>",
    githubClientId: "<id>",
    githubClientSecret: "<value>",
    githubId: "<id>",
    githubInstallationId: "<id>",
    githubPrivateKey: "<value>",
    githubWebhookSecret: "<value>",
  },
  gitlab: {
    accessToken: null,
    applicationId: "<id>",
    expiresAt: null,
    gitProviderId: "<id>",
    gitlabId: "<id>",
    gitlabUrl: "https://late-flame.info/",
    groupName: "<value>",
    redirectUri: "https://corrupt-hammock.com/",
    refreshToken: "<value>",
    secret: "<value>",
  },
  mounts: [],
  name: "<value>",
  ports: [
    {
      applicationId: "<id>",
      portId: "<id>",
      protocol: "tcp",
      publishMode: "host",
      publishedPort: 9546.83,
      targetPort: 2973.68,
    },
  ],
  previewDeployments: [],
  redirects: [],
  registry: {
    createdAt: "1721723330176",
    imagePrefix: "<value>",
    organizationId: "<id>",
    password: "1qbJ_t5c6TAWEsr",
    registryId: "<id>",
    registryName: "<value>",
    registryType: "selfHosted",
    registryUrl: "https://impressionable-knitting.net/",
    username: "Esmeralda.Rice",
  },
  security: [],
  server: {
    appName: "<value>",
    command: "<value>",
    createdAt: "1726141663526",
    description:
      "exotic save supplier vice towards extra-large corral what drowse beneath",
    enableDockerCleanup: false,
    ipAddress: "d2e8:ac2f:cad8:b67b:5eda:fdca:dc08:2e35",
    metricsConfig: "<value>",
    name: "<value>",
    organizationId: "<id>",
    port: 982.43,
    serverId: "<id>",
    serverStatus: "active",
    sshKeyId: "<id>",
    username: "Julien_Murazik",
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

