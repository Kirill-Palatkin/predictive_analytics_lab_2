## Основные файлы
- `lab_2.ipynb` - Jupyter Notebook с полным пайплайном решения
- `requirements.txt` - зависимости

## Запуск

```powershell
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

## Результаты

Сравнивались OLS, Ridge, Random Forest и HistGradientBoosting. Лучшая модель на валидации — OLS.

| Метрика на тесте | Значение |
|---|---:|
| MAE | 0,0626 |
| RMSE | 0,0770 |
| MAPE | 35,66% |
| WAPE | 29,85% |
| Точность направления | 58,47% |
