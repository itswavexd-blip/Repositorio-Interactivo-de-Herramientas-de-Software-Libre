# Wazuh

**Licencia:** GPL v2

## Descripción
Plataforma de seguridad abierta con HIDS, análisis de logs, monitoreo de integridad y dashboard sobre Elastic Stack.

## Sistemas operativos compatibles
- Windows (agentes)
- macOS (agentes)
- Linux (servidor y agentes)

## Enlace oficial
- https://wazuh.com/

### Ejemplo básico (Docker Compose - demo)
```bash
curl -sO https://packages.wazuh.com/4.7/docker-compose.yml
docker compose -f docker-compose.yml up -d
# Accede al dashboard en https://localhost:5601
```

