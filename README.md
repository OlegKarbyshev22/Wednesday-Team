## Структура проекта

- `train_data.pqt`: Тренировочный набор данных в формате Parquet.
- `test_data.pqt`: Тестовый набор данных в формате Parquet.
- `cluster_weights.xlsx`: Excel файл, содержащий веса кластеров.
- `sample_submission.csv`: Пример файла для отправки результатов.
- `baseline.csv`: Файл с предсказаниями для тестового набора данных.
- `CLTV_model.ipynb`: Основной скрипт, реализующий весь процесс от предобработки данных до предсказания и оценки модели.

## Зависимости

Для запуска проекта необходимы следующие библиотеки:

- `numpy`
- `pandas`
- `xgboost`
- `scikit-learn`
- `pyarrow` (для работы с форматом Parquet)
- `openpyxl` (для работы с Excel файлами)

Установите их с помощью pip:

```bash
pip install numpy pandas xgboost scikit-learn pyarrow openpyxl
