# dvmn-4-api-3
dvmn - API веб-сервисов - Урок 3. Улучшаем утилиту

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
* если агурмент ссылка на сайт:
```bash
python3 main.py ya.ru
Your bitlink: bit.ly/2t7hCiD
```
* если агурмент ссылка на сайт:
```bash
python3 main.py bit.ly/2t7hCiD
The number of clicks on the link: 5
```
