---
id: logs
title: Logs
description: "Logs"
---

Like any other integration this logs to the `home-assistant.log` file.

To enable `debug` logging, add this to your `configuration.yaml`:

```yaml title="configuration.yaml"
logger:
  default: info
  logs:
    hacs: debug
    custom_components.hacs: debug
    queueman: debug
    aiogithubapi: debug
```
