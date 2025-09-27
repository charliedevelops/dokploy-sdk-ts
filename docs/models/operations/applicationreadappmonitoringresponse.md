# ApplicationReadAppMonitoringResponse


## Supported Types

### `operations.ApplicationReadAppMonitoringResponseBody`

```typescript
const value: operations.ApplicationReadAppMonitoringResponseBody = {
  block: [
    {
      time: "<value>",
      value: {
        readMb: "<value>",
        writeMb: "<value>",
      },
    },
  ],
  cpu: [],
  disk: [],
  memory: [
    {
      time: "<value>",
      value: {
        total: "<value>",
        used: "<value>",
      },
    },
  ],
  network: [
    {
      time: "<value>",
      value: {
        inputMb: "<value>",
        outputMb: "<value>",
      },
    },
  ],
};
```

### `models.ErrorT`

```typescript
const value: models.ErrorT = {
  code: "<value>",
  message: "<value>",
};
```

