# access-control

1. **Кейс** - Инфотекс(Разработка системы безопасности управления доступом)
2. **План**
- [X] Сервер для управления ключами и замками
- [X] Эмуляция ключа
- [X] Эмуляция замка

**Стек**
- [X] Сервер - FastAPI [[Репозиторий с бекендом]](https://github.com/HITSEdu/access-control-api)
- [X] Клиент администратора - React [[Репозиторий с фронтендом]](https://github.com/HITSEdu/access-control-frontend)
- [X] Эмуляция ключа [[Репозиторий с ключом]](https://github.com/HITSEdu/access-control-key)
- [X] Эмуляция замка [[Репозиторий с замком]](https://github.com/HITSEdu/access-control-lock)
- [X] Алгоритм - OpenSSL(HMAC SHA256)

**Технологии**
* Фронтенд: Next.js, React, Tailwind
* Бекенд: FastAPI, Docker, PostgreSQL
* Криптография: С++, OpenSSL/SHA256, Boost

3. **Дополнительно**
- [X] Админка
- [X] Управление сроком жизни ключа
- [X] Изменения пароля после успешной верификации ключа(автономность работы)
- [X] Замок ограничивает количество попыток
- [X] История доступа

![Примерная архитектура](./arch.png)
![Access](./access.png)
![Refresh](./refresh.png)
