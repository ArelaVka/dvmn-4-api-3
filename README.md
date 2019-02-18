# dvmn-4-api-3
dvmn - API веб-сервисов - Урок 3. Улучшаем утилиту

Скрипт позволяет получить сокращенный url с помощью сервиса [bitly](https://bitly.com/) или получить информацию о количестве кликов по уже созданной ранее сокращенной ссылке (bitlink).

## Для использования необходимо
* установить python3
* установить необходимые зависимости (используя pip или pip3):
```bash
pip3 install -r requirements.txt
```
* добавить файл .env, содержащий api-token сайта bitly. пример:
```
TOKEN=<api-token>
```
## Пример использования
* если аргумент ссылка на сайт:
```bash
python3 main.py ya.ru
Your bitlink: bit.ly/2t7hCiD
```
* если аргумент bitlink:
```bash
python3 main.py bit.ly/2t7hCiD
The number of clicks on the link: 5
```
