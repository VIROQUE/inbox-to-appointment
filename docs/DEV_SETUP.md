# Dev Setup (Local)
Prereqs: Docker Desktop, Git

Start:
  docker compose up -d
  open https://localhost

Health:
  docker compose ps
  curl -ik https://localhost/webhook/hello

Stop:
  docker compose down

Secrets:
  Keep .env local (never commit). Use .env.example for teammates.
