# Kyverno Policies

This repository keeps CI-time Kyverno validation policies here.

Layout:

- `policies/base`
  Common low-noise policies applied to every rendered chart in pull requests.
- `policies/test`
  Test-environment policies applied when the PR base branch is `test`.
- `policies/prod`
  Production-environment policies applied when the PR base branch is `prod`.

The current PR gate uses the Kyverno CLI against rendered Helm manifests and uploads the rendered output and policy reports as workflow artifacts.
