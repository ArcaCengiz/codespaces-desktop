# codespaces-desktop
## Instructions
1. `docker compose up`
1. Perform install
1. Delete line `BOOT: ...` from `docker-compose.yml`

## Usage
Perform install when running for the first time, then run
``` bash
docker compose up
```
to start the VM. The number of CPU cores and RAM size can be changed by changing `CPU_CORES` and `RAM_SIZE` in `docker-compose.yml`. View the amount of free RAM with
``` bash
free -h
```