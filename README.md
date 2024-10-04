# Cadmus LON API

- [Cadmus LON models](https://github.com/vedph/cadmus-lon)
- [Cadmus LON app](https://github.com/vedph/cadmus-lon-app)

🐋 Quick Docker image build (not just `docker build . -t vedph2020/cadmus-lon-api:0.0.7 -t vedph2020/cadmus-lon-api:latest` because we need to distinguish between X86 and ARM for CPU like M2, so I added `--platform=$BUILDPLATFORM` in Dockerfile):

    docker build . --build-arg BUILDPLATFORM=linux -t vedph2020/cadmus-lon-api:0.0.7 -t vedph2020/cadmus-lon-api:latest

    docker build . --build-arg BUILDPLATFORM=arm64 -t vedph2020/cadmus-lon-api_arm:0.0.7 -t vedph2020/cadmus-lon-api_arm:latest

(replace with the current version).

This is a Cadmus API layer customized for the PRJ project. Most of its code is derived from shared Cadmus libraries.

## History

- 2024-10-04: updated works thesaurus.

### 0.0.7

- 2024-09-28: updated packages (new endpoints in API).
- 2024-09-23: added bibliography to person facet and updated packages.

### 0.0.6

- 2024-08-30: updated packages.

### 0.0.5

- 2024-07-29:
  - updated packages.
  - added note part with role `sign` to config.

### 0.0.4

- 2024-07-19: added person item.

### 0.0.3

- 2024-07-17: updated packages.
- 2024-07-15: updated packages.
- 2024-07-02: thesauri.
- 2024-06-30: updated packages.

### 0.0.2

- 2024-06-25:
  - updated packages.
  - seeder categories configuration.
- 2024-06-18: updated thesauri and packages.
