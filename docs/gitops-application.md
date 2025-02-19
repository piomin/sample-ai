# ai-lab-template-gitops

# Gitops Repo Patterns

This repository contains an HTTP Gitops repository format component for use as the AI-Lab Gitops template.

## HTTP

This contains a deployment with the following characteristics:

**Model service image** `quay.io/ai-lab/llamacpp_python:latest` **listening on port** `8001`.

**App interface image** `quay.io/redhat-ai-dev/ai-template-bootstrap-app:latest` **listening on port** `8501` for service and routing.

This matches the current AI-Lab software template default deployment.