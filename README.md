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
