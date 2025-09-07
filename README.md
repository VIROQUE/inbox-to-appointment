# inbox-to-appointment (local dev)

Stack: Docker + Postgres + n8n + Caddy (local HTTPS)

## Run
docker compose up -d
open https://localhost   # Basic Auth enabled (ask Mehdi for password)

## Hello-World webhook
GET https://localhost/webhook/hello  ->  {"ok": true, "msg": "hello from n8n"}

## Notes
- .env holds real secrets and MUST NOT be committed
- Use .env.example to set up local env
