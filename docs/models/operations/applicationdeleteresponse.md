# ApplicationDeleteResponse


## Supported Types

### `operations.ApplicationDeleteResponseBody`

```typescript
const value: operations.ApplicationDeleteResponseBody = {
  name: "<value>",
  environmentId: "<id>",
  environment: {
    environmentId: "<id>",
    name: "<value>",
    description: "during partially greatly worth topsail personal salty tag",
    createdAt: "1730846746403",
    env: "<value>",
    projectId: "<id>",
    project: {
      projectId: "<id>",
      name: "<value>",
      description:
        "er opposite loyally following thyme reservation abaft for feline",
      createdAt: "1718849910278",
      organizationId: "<id>",
      env: "<value>",
    },
  },
  domains: [
    {
      domainId: "<id>",
      host: "jittery-digit.net",
      https: true,
      port: 326.66,
      path: null,
      serviceName: "<value>",
      domainType: "preview",
      uniqueConfigKey: 1330.28,
      createdAt: "1719839158689",
      composeId: "<id>",
      customCertResolver: "<value>",
      applicationId: "<id>",
      previewDeploymentId: "<id>",
      certificateType: "letsencrypt",
      internalPath: "<value>",
      stripPath: false,
    },
  ],
  deployments: [
    {
      deploymentId: "<id>",
      title: "<value>",
      description: "wherever blah on",
      status: "running",
      logPath: "<value>",
      pid: "<id>",
      applicationId: "<id>",
      composeId: "<id>",
      serverId: "<id>",
      isPreviewDeployment: false,
      previewDeploymentId: "<id>",
      createdAt: "1729638788576",
      startedAt: "<value>",
      finishedAt: "<value>",
      errorMessage: "<value>",
      scheduleId: "<id>",
      backupId: "<id>",
      rollbackId: "<id>",
      volumeBackupId: "<id>",
    },
  ],
  mounts: [],
  redirects: [],
  security: [
    {
      securityId: "<id>",
      username: "Rosa87",
      password: "xzR4aFeR4FACH1P",
      createdAt: "1731886669509",
      applicationId: "<id>",
    },
  ],
  ports: [
    {
      portId: "<id>",
      publishedPort: 9389.23,
      publishMode: "host",
      targetPort: 295.36,
      protocol: "udp",
      applicationId: "<id>",
    },
  ],
  registry: {
    registryId: "<id>",
    registryName: "<value>",
    imagePrefix: "<value>",
    username: "Ruben.Luettgen",
    password: "EBOxAWfLquzRh44",
    registryUrl: "https://teeming-behest.name/",
    createdAt: "1705985066217",
    registryType: "cloud",
    organizationId: "<id>",
  },
  github: {
    githubId: "<id>",
    githubAppName: "<value>",
    githubAppId: null,
    githubClientId: "<id>",
    githubClientSecret: "<value>",
    githubInstallationId: "<id>",
    githubPrivateKey: "<value>",
    githubWebhookSecret: "<value>",
    gitProviderId: "<id>",
  },
  gitlab: {
    gitlabId: "<id>",
    gitlabUrl: "https://queasy-dream.net",
    applicationId: "<id>",
    redirectUri: "https://everlasting-coil.net",
    secret: "<value>",
    accessToken: "<value>",
    refreshToken: null,
    groupName: "<value>",
    expiresAt: 4249.75,
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
    giteaUrl: "https://rundown-cutlet.name/",
    redirectUri: "https://apt-ceramics.org/",
    clientId: "<id>",
    clientSecret: "<value>",
    gitProviderId: "<id>",
    accessToken: null,
    refreshToken: "<value>",
    expiresAt: 9579.21,
    scopes: "<value>",
    lastAuthenticatedAt: 9244.39,
  },
  server: {
    serverId: "<id>",
    name: "<value>",
    description: null,
    ipAddress: "4d8b:bd93:ccca:ee95:aaa5:ebce:fd5a:4bb6",
    port: 7015.45,
    username: "Norwood_Gorczany",
    appName: "<value>",
    enableDockerCleanup: true,
    createdAt: "1725934748180",
    organizationId: "<id>",
    serverStatus: "active",
    command: "<value>",
    sshKeyId: "<id>",
    metricsConfig: [
      "<value 1>",
    ],
  },
  previewDeployments: [],
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

