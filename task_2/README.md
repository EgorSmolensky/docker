
## Команды для создания образа и контейнера для этого проекта

```
docker build . -t my_django_pr
docker run -p 8000:8000 my_django_pr
```

Примеры запросов для работы с проектом находятся в файле `requests-examples.http`
