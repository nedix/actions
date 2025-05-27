# actions

## Secrets

| **Name**          | **Purpose**                       | **Default**       | **Required**      |
|-------------------|-----------------------------------|-------------------|-------------------|
| GH_PAT            | Dependency updates using Renovate |                   | Without GH_APP_ID |
| GH_APP_ID         | Dependency updates using Renovate |                   | Without GH_PAT    |
| GH_APP_PEM        | Dependency updates using Renovate |                   | With GH_APP_ID    |
| REGISTRY_DOMAIN   | Package registry domain           | 'ghcr.io'         | No                |
| REGISTRY_PATH     | Package registry path             | github.repository | No                |
| REGISTRY_USERNAME | Package registry username         | github.author     | No                |
| REGISTRY_PASSWORD | Package registry password         | github.token      | No                |

## PAT permissions

**Account:**

| Permission      | Access    |
|-----------------|-----------|
| Email addresses | Read-only |

**Repository:**

| Permission        | Access         |
|-------------------|----------------|
| Administration    | Read-only      |
| Commit statuses   | Read and write |
| Contents          | Read and write |
| Dependabot alerts | Read-only      |
| Issues            | Read and write |
| Metadata          | Read-only      |
| Pull requests     | Read and write |
| Workflows         | Read and write |
