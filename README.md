# Alpine flyway Docker Container
![stars](https://img.shields.io/docker/stars/ringo/flyway.svg?colorA=30B8E9&colorB=FFD32E) ![pulls](https://img.shields.io/docker/pulls/ringo/flyway.svg?colorA=30B8E9) ![automated build](https://img.shields.io/docker/automated/ringo/flyway.svg?colorA=30B8E9) ![build status](https://img.shields.io/docker/build/ringo/flyway.svg?colorA=30B8E9)

- Alpine Linux based.

## Configurations

- `-v /flyway/conf/dir:/opt/flyway/conf`
- `-v /flyway/sql/dir:/opt/flyway/sql`

## Run

```bash
docker pull ringo/flyway
docker run --rm ringo/flyway
```

## Build
```bash
make
```
