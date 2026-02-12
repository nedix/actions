# actions


## Configuration


### Secrets

| **Name**          | **Purpose**           | **Default**       | **Required**      |
|-------------------|-----------------------|-------------------|-------------------|
| GH_PAT            | GitHub authentication |                   | Without GH_APP_ID |
| GH_APP_ID         | GitHub authentication |                   | Without GH_PAT    |
| GH_APP_PEM        | GitHub authentication |                   | With GH_APP_ID    |
| REGISTRY_DOMAIN   | Package publication   | 'ghcr.io'         | No                |
| REGISTRY_PATH     | Package publication   | github.repository | No                |
| REGISTRY_USERNAME | Package publication   | github.author     | No                |
| REGISTRY_PASSWORD | Package publication   | github.token      | No                |


### PAT permissions


#### Account

| Permission      | Access    |
|-----------------|-----------|
| Email addresses | Read-only |


#### Repository

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
