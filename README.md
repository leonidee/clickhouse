
# Connect to cluster

Source credentials:
```shell
source .env
```

Activate env:
```shell
poetry shell
```

Connect to cluster:
```shell
clickhouse-cli --host=$CLICKHOUSE_HOST \
    --port=$CLICKHOUSE_PORT \
    --user=$CLICKHOUSE_USER \
    --arg-password=$CLICKHOUSE_PASSWORD \
    --database=$CLICKHOUSE_DATABASE
```
