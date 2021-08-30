# dev-containers

## Folder structure

```
<project_root>
|-- .devcontainer
    |-- devcontainer.json
    |-- Dockerfile
```

## Devcontainer on remote machine

In `.vscode/settings.json` add:

```json
"docker.host": "ssh://<username>@<host>"
```

**Note**: Docker (or `docker` CLI) needs to be installed on the local machine.