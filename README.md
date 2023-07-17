# Vulnerable VM env
for usage with the [Attack Replay Framework](https://github.com/dial25sd/attack-replay).

## Setup
1. Install docker, make sure it is executable without root privileges.
1. Start all vulnerable services in bash using `./start.sh`.
1. Wait a few minutes for the services to start and get configured correctly.
1. Stop the services anytime using `./stop.sh`.

## Vulnerable services
| CVE | Description | CVSS (Version) | Source | Port |  
| ------ | ------------ | -------------- | ------ | ---- |
| `CVE-2014-3120` | Remote Code Execution in *ElasticSearch* | 6.8 (v2) | [Vulhub](https://github.com/vulhub/vulhub) | `3120` |
| `CVE-2017-9841` | Remote Code Execution in *PHPUnit* | 9.8 (v3) | [Vulhub](https://github.com/vulhub/vulhub) | `9841` |
| `CVE-2019-9193` | Remote Code Execution in *PostgresSQL* | 7.2 (v3) | [Vulhub](https://github.com/vulhub/vulhub) | `9193` |
| `CVE-2021-22205` | Remote Code Execution in *GitLab* | 10.0 (v3) | [Vulhub](https://github.com/vulhub/vulhub) | `22205` |
| `CVE-2021-41773` | Local File Inclusion in *Apache httpd* | 7.5 (v3) | [Vulhub](https://github.com/vulhub/vulhub) | `41773` |
|                | Remote Code Execution in *Apache httpd* |  | [CVE-2021-41773](https://github.com/dial25sd) | `41774` |
| `CVE-2021-42013` | Remote Code Execution in *Apache httpd* | 9.8 (v3) | [Vulhub](https://github.com/vulhub/vulhub) | `42013` |
|                | Local File Inclusion in *Apache httpd* |  | [Vulhub](https://github.com/vulhub/vulhub) | `42014` |                
| `CVE-2021-44228` | Remote Code Execution in *Apache Solr* | 10.0 (v3) | [Vulhub](https://github.com/vulhub/vulhub) | `44228` |
