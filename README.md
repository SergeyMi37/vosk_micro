# VOSK Micro
Пример использования _vosk_ с микрофоном.\
___Примечание:___ дополнительного реализована проверка непристойных слов.

## Установка

Create virtual environment for Windows
``` bash
python -m venv env-win
source env-win/Scripts/activate

Установка зависимостей:
```commandline
pip install -r requirements.txt
```

1. Установка через pip с явным указанием индекса
bash
pip install vosk -i https://pypi.org/simple/ --trusted-host pypi.org
2. Установка конкретной версии
bash
pip install vosk==0.3.45 --index-url https://pypi.org/simple/



Загрузка моделей:
```commandline
wget https://alphacephei.com/vosk/models/vosk-model-small-ru-0.22.zip
unzip vosk-model-small-ru-0.22.zip -d model
```

## Запуск

```commandline
python3 main.py
```
