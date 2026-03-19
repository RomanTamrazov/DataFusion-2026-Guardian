# DataFusion TASK1: Страж
![Project Logo](strazh.png)
Решение задачи антифрода (классификация неподтвержденных операций) для соревнования DataFusion 2026.

## Результат

- `Public score`: **0,12206**
- Основной код: `main-0,122.ipynb`
- Выходной файл: `submission.csv`

## Конфигурация запуска

- GPU: **NVIDIA GeForce RTX 5080**
- RAM: **76 GB**

## Структура проекта

- `main-0,122.ipynb` - ноутбук с полным пайплайном обучения и инференса
- `submission.csv` - файл предсказаний для отправки
- `data/` - входные данные соревнования
- `cache/` - промежуточные кэшированные признаки

## Зависимости:

- `numpy`
- `pandas`
- `polars`
- `scikit-learn`
- `catboost`
- `pyarrow`
- `jupyter`
```bash
pip install numpy pandas polars scikit-learn catboost pyarrow jupyter
```

## Как запустить

1. Положить все файлы датасета в папку `data/`.
2. Открыть `main-0,122.ipynb`.
3. Выполнить все ячейки последовательно (`Run All`).
4. После завершения будет создан `submission.csv`.

## Формат результата

`submission.csv` содержит 2 колонки:

- `event_id`
- `predict`

и готов к загрузке в систему соревнования.

## Контакты: [@Roman_Tamrazov](https://t.me/Roman_Tamrazov)
# Всем удачи! Надеюсь мой код вам поможет с выбиванием топ метрики 0_0
