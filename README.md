# Time series In action 2025

## Как настроить окружение

Cоздаем окружение и ядро для юпитера
```
pip install uv
uv sync --all-extras
source .venv/bin/activate
python -m ipykernel install --user --name=time-series-in-action
```