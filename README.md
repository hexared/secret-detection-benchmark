## Secret detection benchmark repository

### Secrets list
This repository contains a curated list of secrets used for benchmarking secret detection tools. The secrets included in this repository are for testing purposes only and should not be used in production environments.
| File               |  Secrets  | Secret types    |
|--------------------|-----------|-----------------|
|.env                |  3        | generic pass    |
|.ssh/my_sshkey      |  1        | private key     |
|.ssh/ssh_prod       |  1        | private key     |
|app.json            |  3        | JDBC, generic   |
|app.properties      |  3        | generic password|
|config.py           |  2        | GCP, Azure      |
|stack-test.yaml     |  3        | postgresql      |
|config.json         |  4        | JDBC            |
|config2.json        |  3        | JDBC            |
|keycloak.yaml       |  1        | generic secret  |
|oauth_token.json    |  1        | generic token   |
|new_infra.tfstate   |  2        | generic pass    |
|tokens              |  1        | JWT token       |
|google_account.json |  1        | GCP token       |
|settings.toml       |  7        | Everything      |

### Total secrets
The repository contains a total of 36 secrets across various files and formats.

[//]: # (another sneaky password: Pa$$word123!)
