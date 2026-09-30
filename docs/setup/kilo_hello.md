1) Учебный сервис предварительной оценки заявки на заём под ПТС: принимает VIN/год/пробег/стоимость/сумму/срок, считает LTV и возвращает `approve`/`review`/`reject`.
2) `Makefile`: `help`, `up`, `down`, `ps`, `logs`, `install`, `test`, `lint`, `seed`. `docker-compose.yml`: сервисы `backend` (PHP-Slim на :8080) и `db` (MySQL 8), отдельных команд сверх `docker compose up/down/ps/logs` не нашёл — запуск/проверка делаются через `make`.
3) Папка `backend/src/Domain/` (файл `DecisionEngine.php`, пороги берутся из `backend/config/rules.php`).
модель: stg-proxy/training-2026-09-minimax-m3
