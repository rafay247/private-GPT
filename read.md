# Ollama Local Stack

This project runs Ollama and Open WebUI with Docker Compose.

## Services

- `ollama` on `http://localhost:11434`
- `open-webui` on `http://localhdockeost:8030`

## Requirements

- Docker
- Docker Compose (plugin or standalone)

## Run

From this project directory:

```bash
docker compose up -d
```

## Check status

```bash
docker compose ps
```

## View logs

```bash
docker compose logs -f
```

## Stop

```bash
docker compose down
```
