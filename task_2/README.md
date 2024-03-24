# Домашнее задание к лекции «Docker»
## Задание 2.

#### После клонирования репозитория (локально) используйте команду для создания Docker Image (необходимо находиться в папке с файлом Dockerfile)

```docker image build . --tag=stocks_products```

#### После создания Docker Image запустить контейнер можно командой

```docker run -d -p 8000:8000 stocks_products```

Перейдите в браузере по пути http://localhost:8000/api/v1/

Для проверки работоспособности приложения можно использовать VS Code REST Client или Postman.
Примеры запросов находятся в файле [requests-examples.http](requests-examples.http).

