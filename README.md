# WebAPI Java Solution (Todo App) ☕

Учебный проект: REST API для управления задачами (To-Do), написанный на **Java** с использованием **Spring Boot**.

## 🛠 Стек технологий
- **Java** (JDK 17+)
- **Spring Boot** — веб-фреймворк для создания REST API.
- **Spring Data JPA** — работа с базой данных (Hibernate).
- **Maven** — сборка проекта.
- **H2 / PostgreSQL** — база данных (уточни, что именно используешь).

## 📂 Архитектура проекта
Проект разделён на слои для чистоты кода:
- `model/` — сущности базы данных (например, `Task`, `User`).
- `repository/` — интерфейсы для работы с БД (Spring Data JPA).
- `service/` — бизнес-логика (обработка запросов).
- `todoapp/` — контроллеры (эндпоинты для обработки HTTP-запросов).
- `pom.xml` — зависимости Maven.
- `mvnw` — Maven Wrapper (для запуска без установки Maven).

## 🚀 Функционал (CRUD)
- Создание задачи (`POST /tasks`).
- Получение списка задач (`GET /tasks`).
- Получение задачи по ID (`GET /tasks/{id}`).
- Обновление задачи (`PUT /tasks/{id}`).
- Удаление задачи (`DELETE /tasks/{id}`).

## 🏃 Как запустить
1. Убедись, что у тебя установлена **Java** (JDK 17 или выше).
2. Клонируй репозиторий:
   ```bash
   git clone https://github.com/DaniilKiselev88/WebAPI_JavaSolution_PP.git
