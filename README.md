app_v2/
├── api_v1/           # API версия 1
├── core/             # Основные настройки и утилиты
├── models/           # Модели базы данных
├── users/            # Модуль пользователей
│   ├── __init__.py
│   ├── crud.py      # Операции CRUD для пользователей
│   ├── schemas.py   # Pydantic схемы
│   └── views.py     # API эндпоинты пользователей
├── items_views.py    # API эндпоинты для items
├── main.py           # Точка входа в приложение
├── __init__.py
└── config.py         # Конфигурация приложения
