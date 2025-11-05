# Сервис по сохранению просмотренных сериалов
![Node.js](https://img.shields.io/badge/Node.js-6DA55F.svg?logo=node.js&style=flat&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?logo=JavaScript&style=flat&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232a.svg?logo=react&style=flat)
![Static Badge](https://img.shields.io/badge/Tailwind-black?logo=css&color=blue)
![Google Sheets](https://img.shields.io/badge/GoogleSheets-006400?logo=google-cloud&style=flat&logoColor=white)
## О проекте
Добавление просмотренных сериалов в свою коллекцию, удобное отображение всех сериалов в виде карточек с возможностью сортировки сериалов по платформе, стране и т.д.
Также отдельная страница с подробной информацией о сериале.
## Начало
<img width="433" height="64" alt="image" src="https://github.com/user-attachments/assets/e14e40a0-e421-4219-9c39-851c7cb33df8" />

В правом верхнем углу расположено меню, в котором содержится:
- Поле поиска по названию сериала.
- Кнопка с выпадающим списком сортировки сериалов.
- Кнопка загрузить новый сериал.
- Тумблер смены темы тёмная/светлая.
## Сортировка сериалов
<img width="275" height="274" alt="image" src="https://github.com/user-attachments/assets/8efad63a-9683-4487-9284-c9d11274c786" />

В выпадающем списке можно сортировать по категориям:
- Более 30 платформ.
- 10 крупных стран.
- Завершён или продолжается сниматься сериал

Снизу выпадающего списка предусмотрена кнопка сброса сортировки.
## Загрузить сериал
<img width="518" height="614" alt="image" src="https://github.com/user-attachments/assets/481e7dba-5a02-4d99-a36d-ae67485b06c4" />

После нажатия на кнопку Загрузить, появляется модальное окно с параметрами которые необходимо заполнить:
- Название(ru) и Оригинальное название(en)
- Постер(url)
- Рейтинги IMDb и Кинопоиска
- YouTube трейлер загружается по специальному коду:

<img width="311" height="94" alt="image" src="https://github.com/user-attachments/assets/346f2b8d-6e87-4ef0-9de4-c4477579695d" />

- ID кинопоиска указывается из ссылки на сериал(https://www.kinopoisk.ru/film/{ID}/)
- Сезон и серия заполняется по просмотру пользователя
- Год производства сериала
- Выпадающий список Статус, выбирается год продолжения сериала или завершён
- Если сериал завершён появляется новое поле Год завершения
- Выпадающий список Страна, выбор стран
- Выпадающий список Жанр, выбор жанров
- Выпадающий список Платформа, выбор платформы

После заполнения всех полей, необходимо нажать на кнопку Загрузить, данные сохраняются в Google Sheets.
## Детальная информация о сериале
<img width="1618" height="743" alt="image" src="https://github.com/user-attachments/assets/c2a897db-8b84-4171-81fa-b666b417a8a4" />

Содержится вся информация о сериале, с возможностью посмотреть трейлер. Также присутствуют кнопки Назад - вернутся к списку сериалов и Кинопоиск - переход на страницу сериала на платформе Кинопоиск.
## Тёмная/светлая тема
Предусмотрена смена тем на тёмную или светлую.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4a41c862-61ee-47b0-b777-1454e6504662" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0cc25ff0-86c6-4834-a311-14d1eb6ee7d0" />
