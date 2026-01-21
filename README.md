# Baikal

A self-hosted baikal application.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/baikal/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/baikal" ~/.local/srv/docker/baikal
cd ~/.local/srv/docker/baikal
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install baikal
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
