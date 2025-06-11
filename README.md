# Neural Optimizer Project

Проект по исследованию нейронных оптимизаторов с использованием паттернов Strategy, Factory и Builder.

## Требования

- Python 3.10 или выше
- Poetry (менеджер зависимостей)
- Bash

## Установка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/your-username/neural-optimizer-full.git
cd neural-optimizer-full
```

2. Установите Poetry (если еще не установлен):
```bash
curl -sSL https://install.python-poetry.org | python3 -
```

3. Установите зависимости проекта:
```bash
poetry install
```

## Скачивание датасета

Для скачивания датасета выполните следующую команду:
```bash
bash scripts/download_dataset.sh
```

## Запуск проекта

1. Активируйте виртуальное окружение:
```bash
poetry shell
```

2. Запустите основной скрипт:
```bash
python main.py
```

## Структура проекта

- `config/` - конфигурационные файлы
- `data/` - директория для датасетов
- `experiments/` - результаты экспериментов
- `models/` - модели нейронных сетей
- `optimizers/` - реализации оптимизаторов
- `strategies/` - стратегии обучения
- `factories/` - фабрики для создания объектов
- `training/` - скрипты для обучения
- `utils/` - вспомогательные функции

## Конфигурация

Основные параметры проекта можно настроить в файле `config.yaml`.

## Лицензия

MIT 