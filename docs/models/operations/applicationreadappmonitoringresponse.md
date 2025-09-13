# ApplicationReadAppMonitoringResponse


## Supported Types

### `operations.ApplicationReadAppMonitoringResponseBody`

```typescript
const value: operations.ApplicationReadAppMonitoringResponseBody = {
  cpu: [
    {
      value: "<value>",
      time: "<value>",
    },
  ],
  memory: [],
  disk: [],
  network: [
    {
      value: {
        inputMb: "<value>",
        outputMb: "<value>",
      },
      time: "<value>",
    },
  ],
  block: [
    {
      value: {
        readMb: "<value>",
        writeMb: "<value>",
      },
      time: "<value>",
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

