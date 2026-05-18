# Удивительная база данных вакансий

![SQLite Version](https://img.shields.io/badge/sqlite-3.32.3-blue)
![Python Version](https://img.shields.io/badge/python-3.8-blue)

## 📚 Описание проекта

Этот проект представляет собой базу данных для хранения информации о вакансиях. Он позволяет добавлять, обновлять, удалять и запрашивать вакансии с использованием SQL-запросов. Проект построен с использованием **SQLite** и **Python** для управления базой данных.

## 🚀 Установка

1. Склонируйте репозиторий:

    ```bash
    git clone https://github.com/username/repo.git
    cd repo
    ```

2. Установите зависимости:

    ```bash
    pip install -r requirements.txt
    ```

3. Настройте базу данных:

    Выполните следующий скрипт, чтобы инициализировать базу данных SQLite:

    ```bash
    python init_db.py
    ```

## 💻 Использование

После установки базы данных Вы можете начать использовать SQL-запросы для управления вакансиями.

### Примеры использования:

#### Добавление новой вакансии:

```sql
INSERT INTO jobs (title, company, location, salary)
VALUES ('Data Scientist', 'TechCorp', 'New York', 120000);
