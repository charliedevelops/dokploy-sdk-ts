# GitProviderGetAllResponse


## Supported Types

### `operations.GitProviderGetAllResponseBody[]`

```typescript
const value: operations.GitProviderGetAllResponseBody[] = [
  {
    gitProviderId: "<id>",
    name: "<value>",
    providerType: "gitlab",
    createdAt: "1730514244233",
    organizationId: "<id>",
    userId: "<id>",
    gitlab: {
      gitlabId: "<id>",
      gitlabUrl: "https://internal-schedule.org",
      applicationId: "<id>",
      redirectUri: "https://twin-presume.biz",
      secret: "<value>",
      accessToken: "<value>",
      refreshToken: "<value>",
      groupName: "<value>",
      expiresAt: 1740.43,
      gitProviderId: "<id>",
    },
    bitbucket: {
      bitbucketId: "<id>",
      bitbucketUsername: "<value>",
      appPassword: "<value>",
      bitbucketWorkspaceName: "<value>",
      gitProviderId: "<id>",
    },
    github: {
      githubId: "<id>",
      githubAppName: "<value>",
      githubAppId: 4501.86,
      githubClientId: null,
      githubClientSecret: "<value>",
      githubInstallationId: "<id>",
      githubPrivateKey: "<value>",
      githubWebhookSecret: "<value>",
      gitProviderId: "<id>",
    },
    gitea: {
      giteaId: "<id>",
      giteaUrl: "https://insignificant-fishery.biz/",
      redirectUri: "https://nimble-dish.info",
      clientId: "<id>",
      clientSecret: null,
      gitProviderId: "<id>",
      accessToken: "<value>",
      refreshToken: "<value>",
      expiresAt: 8422.95,
      scopes: "<value>",
      lastAuthenticatedAt: null,
    },
  },
];
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  message: "<value>",
  code: "<value>",
};
```

