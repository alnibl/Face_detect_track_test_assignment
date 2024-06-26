### Настройка окружения

Сначала создать и активировать venv:

```bash
python3 -m venv venv
. venv/bin/activate
```

Дальше поставить зависимости:

```bash
make install
```
### Команды

#### Подготовка
* `make install` - установка библиотек

#### Запуск
* `make run_app` - запустить детект видео
* для просмотра открыть в браузере http://127.0.0.1:5000/video_feed

#### Сборка образа
* `make build` - собрать образ. Можно с аргументами `DOCKER_TAG`, `DOCKER_IMAGE`
# face_detect_track
