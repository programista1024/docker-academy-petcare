# 🔧 Rozwiązywanie problemów – Etap 00

## Błąd 403 Forbidden – Apache

```
access to /index.php denied (filesystem path '/var/www/html/index.php') because search permissions are missing
```

🔹 Rozwiązanie:
- Nadaj katalogom nadrzędnym prawo `o+x`
- Jeśli używasz SELinux, dodaj `:z` do volume w docker-compose.yml

## Strona się nie wyświetla

Upewnij się, że `index.php` znajduje się w katalogu `src/`, a nie w katalogu głównym.
