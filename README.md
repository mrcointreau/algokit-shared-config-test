# algokit-shared-config-test

Test consumer repo for validating reusable GitHub Actions workflows from [algokit-shared-config](https://github.com/algorandfoundation/algokit-shared-config).

## Node workflows

| Workflow | Reusable workflows used |
|---|---|
| `node-pr.yml` | `node-ci` |
| `node-release.yml` | `node-ci` → `node-build-zip` → `node-release` |
| `node-prod-release.yml` | `prod-release` |

## Python workflows

| Workflow | Reusable workflows used |
|---|---|
| `python-pr.yml` | `python-ci` |
| `python-release.yml` | `python-release` |
