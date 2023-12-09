# __PROSEPT MATCHING__

Ваш помошник в автоматизации и сопоставлении товаров в вашей базе данных (далее БД) с использовванием высокотехнологичного машинного обучения.


___

### АЛЬФА-ВЕРСИЯ

[https://prediction-service.ddns.net/]


[https://prediction-service.ddns.net/api/swagger/]

[https://prediction-service.ddns.net/]: <https://prediction-service.ddns.net/>
[https://prediction-service.ddns.net/api/swagger/]: <https://prediction-service.ddns.net/api/swagger/>

___

### ВВЕДЕНИЕ

PROSEPT MATCHING - это веб-приложение, которое поможет специалистам быстро и эффективно сопоставлять товары производителя с товарами дилеров в БД и вести удобную статистику.
___
### ОПИСАНИЕ

В процессе разработки проекта были реализованы:
- интуитивно понятный интерфейс;
- предварительный анализ данных и машиннное обучение;
- удобное хранение и работа с записями в БД.
___

### ТЕХНОЛОГИИ

PROSEPT MATCHING разработан с использованием следующих технологий:

- [Python] (v.3.11) - целевой язык программирования backend;
- [Django] (v.4.2) - высокоуровневый веб-фреймворк;
- [Django REST framework] (v.3.14) - инструмент для создания Web API;
- [PostgreSQL] (v.13.10) - объектно-реляционная база данных;
- [Celery] (v.5.3) - распределенная очередь задач;
- [Redis] (v.5.0) - резидентная система управления NoSQL базами данных, брокер сообщений Celery;
- [PyJWT] (v.2.8) - плагин, предоставляющий JSON Web Token аутентификацию для Django REST Framework, разработанную в соответствии со стандартом RFC 7519;
- [Gunicorn] (v.21.2) - Python WSGI HTTP-сервер для UNIX;
- [Nginx] - HTTP-сервер и обратный прокси-сервер;
- [Docker] (v.24.0) - инструмент для автоматизирования процессов разработки, доставки и запуска приложений в контейнерах.


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Celery](https://a11ybadges.com/badge?logo=celery)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![PyJWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

- [JavaScript] (v.1.8) - целевой язык программирования frontend;
- [React] (v.18.2) - библиотека JavaScript для разработки пользовательских интерфейсов (UI) веб-приложений;
- [React Router] (v.6.15) - библиотека React для маршрутизации страниц;
- [Redux] (v.8.1) - библиотека  управления состоянием JavaScript приложений;
- [HTML5] - целевой язык для структурирования и представления;
- [CSS3] -  целевой язык декорирования и описания внешнего вида документа (веб-страницы).

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23323330.svg?style=for-the-badge&logo=html5&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/CSS3-%23323330.svg?style=for-the-badge&logo=css3&logoColor=%23F7DF1E)

- [Pandas] - программная библиотека на языке Python для обработки и анализа данных;
- [Numpy] - библиотека предназначенная для работы с многомерными массивами;
- [Nltk] - пакет библиотек и программ для символьной и статистической обработки естественного языка, написанных на языке программирования Python;
- [Faiss] - разработка команды Facebook AI Research для быстрого поиска ближайших соседей и кластеризации в векторном пространстве;
- [Sklearn] - библиотека, предназначенная для машинного обучения;
- [Spacy] - программная библиотека с открытым исходным кодом для расширенной обработки естественного языка.
![Pandas](https://img.shields.io/badge/Pandas-%23323330.svg?style=for-the-badge&logo=pandas&logoColor=%23F7DF1E)
![Numpy](https://img.shields.io/badge/Numpy-%23323330.svg?style=for-the-badge&logo=numpy&logoColor=%23F7DF1E)
![Nltk](https://img.shields.io/badge/Nltk-%23323330.svg?style=for-the-badge&logo=nltk&logoColor=%23F7DF1E)
![Faiss](https://img.shields.io/badge/Faiss-%23323330.svg?style=for-the-badge&logo=faiss&logoColor=%23F7DF1E)
![Sklearn](https://img.shields.io/badge/Sklearn-%23323330.svg?style=for-the-badge&logo=sklearn&logoColor=%23F7DF1E)
![Spacy](https://img.shields.io/badge/Spacy-%23323330.svg?style=for-the-badge&logo=Spacy&logoColor=%23F7DF1E)
___


### РАЗВЕРТКА

✅ Создать корневую папку с проектом (предлагается "hakaton") и перейти в неё

```
mkdir hakaton
cd hakaton
```

✅ Загрузить актуальные версии frontend и backend

```
git clone git@github.com:Prosept-4/frontend.git
git clone git@github.com:Prosept-4/backend_Django.git
```

✅ Перейти в папку backend

```
cd backend_Django/
```

✅ Создать файл переменных окружения из примера

```
cp .env.example .env
```

✅ Изменить переменные окружения (если необходимо) (!согласуйте DB_HOST с настройками в docker-compose сборке!)
```
(на примере редактора Nano)
nano .env
```

✅ Перейти в корневую папку backend
```
cd ..
```

✅ Запустить Docker (убедитесь, что `docker daemon` запущен в системе!)

```
docker-compose up --build
```

✅ Проверить доступность проекта на

```
http://localhost:8000/
```

✅ Документация доступна на

```
http://localhost:8000/api/swagger/
```

___

### ЛИЦЕНЗИЯ

MIT

___

### PRODUCT MANAGER

[Константин Чернышов]

### КОМАНДА FRONTEND
[Богдан Исаченко]

[Кирилл Красноруцкий]

### КОМАНДА BACKEND

[Кирилл Широков]

[Максим Головин]

### КОМАНДА DATA SIENCE

[Денис Минайчев]

[Андрей Мукосеев]

[Ирина Носач]



[Константин Чернышов]: <https://t.me/RoofMountain/>
[Богдан Исаченко]: <https://t.me/doctorian/>
[Кирилл Красноруцкий]: <https://t.me/Red_Handed_Guy/>
[Кирилл Широков]: <https://t.me/Kirill_Sh_ow/>
[Максим Головин]: <https://t.me/PrimeStr/>
[Денис Минайчев]: <https://t.me/Serios_Den/>
[Андрей Мукосеев]: <https://t.me/andreichpog/>
[Ирина Носач]: <https://t.me/Lola_bsl/>


[Python]: <https://www.python.org/>
[Django]: <https://www.djangoproject.com/>
[Django REST framework]: <https://www.django-rest-framework.org/>
[PostgreSQL]: <https://www.postgresql.org/>
[Celery]: <https://docs.celeryq.dev/en/stable/>
[Redis]: <https://redis.io/>
[PyJWT]: <https://pyjwt.readthedocs.io/en/latest/>
[Gunicorn]: <https://gunicorn.org/>
[Nginx]: <https://nginx.org/en/>
[Docker]: <https://www.docker.com/>

[JavaScript]: <https://www.javascript.com/>
[TypeScript]: <https://www.typescriptlang.org/>
[React]: <https://react.dev/>
[React Router]: <https://reactrouter.com/en/main/>
[Vite]: <https://vitejs.dev/>
[Redux]: <https://redux.js.org/>
[Yup]: <https://github.com/jquense/yup>
[HTML5]: <https://htmlbook.ru/html5>
[CSS3]: <https://htmlbook.ru/css3>

