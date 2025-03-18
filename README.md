# Cadmus LON API

- [Cadmus LON models](https://github.com/vedph/cadmus-lon)
- [Cadmus LON app](https://github.com/vedph/cadmus-lon-app)

- 🐋 Quick Docker image build (you need to have a `buildx` container):

```bash
docker buildx create --use

docker buildx build . --platform linux/amd64,linux/arm64,windows/amd64,windows/arm64 -t vedph2020/cadmus-lon-api:1.0.1 -t vedph2020/cadmus-lon-api:latest --push
```

(replace with the current version).

This is a Cadmus API layer customized for the PRJ project. Most of its code is derived from shared Cadmus libraries.

## History

### 2.0.0

- 2025-03-18: updated packages (bumped Cadmus API to v11).

### 1.0.2

- 2025-01-29: updated packages.
- 2025-01-06: updated packages.

### 1.0.1

- 2024-11-23: ⚠️ upgraded to .NET 9.
- 2024-10-21: updated packages.
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
