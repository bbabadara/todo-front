# todo-front

Frontend de l'application Todo (TP infra DevOps). SPA servie par nginx, badge d'environnement injecté (`__ENV_NAME__` -> `ENV_NAME`) au démarrage via `/etc/nginx/templates`.

## Image Docker

- `ghcr.io/bbabadara/todo-front:latest` (dev/prod)
- Déployée sur le serveur par Ansible (`/opt/todo/app/docker-compose.yml`) puis les workflows GitHub Actions.