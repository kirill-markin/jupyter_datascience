# Разворачивает jupyter_datascience

## Первый запуск

```shell
git clone https://github.com/Kirmark/jupyter_datascience.git && 
cd jupyter_datascience && 
chmod +x startup.sh && 
sudo ./startup.sh  
```

## Перезапуск

```shell
cd jupyter_datascience && 
git pull && 
sudo ./startup.sh  
```

## Соединение с контейнером

```shell
sudo docker exec -it jupyter_datascience_instance bash
```
