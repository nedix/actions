# actions

## Secrets

| **Name**          | **Purpose**                       | **Default**       | **Required**      |
|-------------------|-----------------------------------|-------------------|-------------------|
| GH_PAT            | Dependency updates using Renovate | *empty*           | Without GH_APP_ID |
| GH_APP_ID         | Dependency updates using Renovate | *empty*           | Without GH_PAT    |
| GH_APP_PEM        | Dependency updates using Renovate | *empty*           | With GH_APP_ID    |
| REGISTRY_DOMAIN   | Package registry domain           | 'ghcr.io'         | No                |
| REGISTRY_PATH     | Package registry path             | github.repository | No                |
| REGISTRY_USERNAME | Package registry username         | github.author     | No                |
| REGISTRY_PASSWORD | Package registry password         | github.token      | No                |
