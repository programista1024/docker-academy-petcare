# 🐧 Linux: Etap 00 – PHP + Apache

## Uruchomienie

1. Skopiuj `.env.example` jako `.env`
2. Uruchom kontener:
```bash
docker-compose up --build
```
3. Przejdź do: [http://localhost:8080](http://localhost:8080)

## SELinux

Jeśli używasz SELinux (Fedora, CentOS, RHEL), dodaj `:z` do volume:

```yaml
volumes:
  - ./src:/var/www/html:z
```
W przeciwnym razie Apache może nie mieć dostępu do plików.

Zobacz też [../troubleshooting.md](../troubleshooting.md)
