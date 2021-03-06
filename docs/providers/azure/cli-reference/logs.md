<!--
title: Serverless Framework Commands - Azure Functions - Logs
menuText: logs
menuOrder: 7
description: View logs of your Azure Functions Function within your terminal using the Serverless Framework
layout: Doc
-->

<!-- DOCS-SITE-LINK:START automatically generated  -->

### [Read this on the main serverless docs site](https://www.serverless.com/framework/docs/providers/azure/cli-reference/logs)

<!-- DOCS-SITE-LINK:END -->

# Azure - Logs

Lets you watch the logs of a specific function.

```bash
serverless logs -f hello
```

## Options

- `--function` or `-f` The function you want to fetch the logs for. **Required**

## Examples

### Azure Functions

```bash
serverless logs -f hello
```

This will stream all future logs for a given Function.
