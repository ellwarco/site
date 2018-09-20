---
title: 'Serverless Framework Commands - Apache OpenWhisk - Plugin Uninstall'
menuText: 'Plugin Uninstall'
menuOrder: 15
description: 'Uninstall a Serverless plugin'
layout: Doc
gitLink: /docs/providers/openwhisk/cli-reference/plugin-uninstall.md
---

# Plugin Uninstall

Uninstall a Serverless plugin and remove it from the services `plugins` array.

```bash
serverless plugin uninstall --name pluginName
```

## Options
- `--name` or `-n` The plugins name. **Required**.

## Provided lifecycle events
- `plugin:uninstall:uninstall`

## Examples

### Remove the `serverless-webpack` plugin

```bash
serverless plugin uninstall --name serverless-webpack
```