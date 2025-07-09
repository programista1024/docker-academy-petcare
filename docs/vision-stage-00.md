# 🎯 Etap 00 – PHP + Apache

**Cel:**  
Wprowadzenie do Dockera przy użyciu najprostszego możliwego scenariusza: statyczna aplikacja PHP hostowana na Apache.

**Zakres:**  
- Budowa obrazu na bazie `php:8.1-apache`
- Udostępnienie prostego pliku `index.php`
- Utrwalenie podstaw `Dockerfile`, `docker-compose`, bind volume
- Użytkownicy mają zobaczyć stronę powitalną w przeglądarce

**Docelowy efekt końcowy:**  
Użytkownik rozumie jak:
- uruchomić kontener
- zamontować lokalny kod do kontenera
- rozwiązać problem z uprawnieniami na Linuxie (SELinux)
