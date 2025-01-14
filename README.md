# Шардирование

## Как запустить

### Переход в папку с финальным решением
```shell
cd sharding-repl-cache
```

### Запуск mongodb и приложения

```shell
docker compose up -d
```

### Подключение к серверу конфигурации и инициализация

```shell
./scripts/config-server-init.sh
```


### Инициализация шардов  с наборами реплик

```shell
./scripts/shards-init.sh
```


### Инициализация роутера и наполнение его тестовыми данными

```shell
./scripts/router-init.sh
```
