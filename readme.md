# ДЗ Тема: Основи технології Docker

Створіть віртуальне оточення то встановіть необхідні бібліотеки

```
poetry env use python3.12
eval $(poetry env activate)
poetry add $(cat requirements.txt | awk '{print $1}')
poetry install --no-root
poetry env info
```
