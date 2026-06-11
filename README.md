
# Home DNS & AdBlock Server (Dockerized)
## Опис проєкту
Локальний DNS-сервер та блокувальник реклами мережевого рівня, розгорнутий на домашньому сервері (Fedora Linux) за допомогою Docker Compose. 

## Стек технологій
* Linux Server Administration
* Docker & Docker Compose
* Networking (DNS, TCP/UDP, Router Configuration)

## Як розгорнути
1. Клонувати репозиторій.
2. Створити файл `.env` на базі `.env.example`.
3. Запустити інфраструктуру: `docker compose up -d`.
4. Прописати статичну IP-адресу сервера як основний DNS у налаштуваннях домашнього DHCP/роутера.

**Автор:** Danyil Kulbachuk
