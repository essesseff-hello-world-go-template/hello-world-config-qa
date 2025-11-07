# Hello World Config - QA

Helm chart for QA environment.

## Configuration

- **Environment**: QA
- **Auto-Deploy**: No (manual via essesseff)
- **Namespace**: `essesseff-hello-world-go-template`
- **Ingress**: `example.com/hello-world-qa`

## Updates

This repository in combination with the app-of-apps environment-specific deployment config determine when/if/how deployments occur via Argo CD.  This repository is updated by essesseff platform when QA deployments are to occur as per QA Engineer manual decision.

Typically, only the values.yaml file should be manually altered, while any/all other changes in the repository are made via essesseff deployment orchestration.
