# finflow

### Описание
TODO
___
### Запуск
Локальный запуск
```commandline
uvicorn main:app --reload
```

Запуск в Docker
```commandline
docker build . -t deposit_app:latest
docker run -d -p 7777:8000 deposit_app
```
___
### Тестирование
Проверка покрытия кода тестами
```commandline
coverage run -m pytest
coverage report
```