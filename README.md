# vk_faq_bot

### Используемые инструменты:
- Для взаимодействия с ВК API использовалась библиотека https://github.com/timoniq/vkbottle
- Для семантического поиска использовалась модель "xlm-r-40langs-bert-base-nli-stsb-mean-tokens" из репозитория https://github.com/UKPLab/sentence-transformers

### Установка
1. Установить виртуальное окружение:
```
python -m venv env
```
Активировать виртуальное окружение:
* Linux:
```
source ./env/bin/activate
```
* Windows:
```
.\env\Scripts\activate.bat
```
2. Затем в терминале:
```
pip3 install -r requirements.txt
```
3. Запуск бота:
* Перед запуском необходимо указать токен в main.py в строке:
```
bot = Bot(<Ваш токен>, debug="DEBUG")
```
После этого ввести в терминале:
```
  python main.py
```

### Использование

В data.csv содержится список вопросов. Чтобы бот понимал другие вопросы, нужно изменить этот файл и перезапустить бота (шаг 3 из раздела "Установка")
