<div align="center">
    <h1>Привет, меня зовут UglyGhoulChrist</h1>
</div>

---

<h2 align="center">Мои проекты:</h2>

### Телеграм боты

#### Викторины для детей и взрослых

Бот задает вопросы на разные темы:

- животные
- космос
- ...

##### Технологии, применённые в проекте:

- telegraf.js
- TypeScript

[Code](https://github.com/UglyGhoulChrist/tg-bot-quizzes-telegraf-ts)
[Проект в телеграм](https://t.me/QuzzesUGC_bot)

---

#### JavaScript 'Что будет выведено в консоль?'

Бот задает вопросы по JavaScript. Для каждого вопроса доступно четыре варианта
ответа, один из которых является верным. После выбора ответа бот предоставит
объяснение к вопросу и сообщит, правильно ли был выбран ответ.

Вопросы взяты взяты с [https://my-js.org] - 231 вопрос.

Для парсинга вопросов из файла Markdown в объект TypeScript была создана
[утилита](https://github.com/UglyGhoulChrist/converter-quiz-md-to-ts-deno).

##### Технологии, применённые в проекте:

- grammY
- TypeScript
- rollup.js

[Code](https://github.com/UglyGhoulChrist/tg-bot-quiz-js-grammy-ts)
[Проект в телеграм](https://t.me/JavaScriptQuiz_bot)

---

### Next.js

#### ToDo on NextJS + Zustand

##### Страницы:

- Главная:
  - Список задач
  - Форма добавления новой задачи
  - Кнопки управления задачами

##### Список задач — позволяет:

- Добавлять задачи
- Отмечать задачу выполненной
- Возобновлять задачу
- Удалять задачу
- Удалять все задачи
- Удалять выполненные задачи

Хранит задачи в LocalStorage браузера.

##### Технологии, применённые в проекте:

- NextJS
- TypeScript
- Zustand
  - persist localStorage

[Code](https://github.com/UglyGhoulChrist/todo-nextjs-zustand.git)\
[Проект на платформе Vercel](https://todo-nextjs-zustand.vercel.app/)

---

#### Игра в города России, человек против компьютера

##### Страницы:

- Главная:
  - Список названных городов
  - Форма ввода города

##### Технологии, применённые в проекте:

- NextJS (client & server)
- TypeScript

[Code](https://github.com/UglyGhoulChrist/city-game-nextjs.git)\
[Проект на платформе Vercel](https://city-game-nextjs.vercel.app/)

---

#### QUIZ по JavaScript 'Что будет выведено в консоль?'

##### Страницы:

- Главная: _Server-Side Rendering (SSR)_
  - header
    - Logo
    - кнопка получения 20 случайных вопросов
    - счётчик правильных / неправильных ответов ( хранятся в localStorage )
  - 20 карточек
    - вопросы по JS с подсвеченным синтаксисом
    - форма с вариантами ответа
    - по нажатию на кнопку всплывает модальное окно с правильным ответом и
      пояснением

##### Технологии, применённые в проекте:

- NextJS (client & server)
- TypeScript
- GitFlow
- package:
  - highlight.js
  - zustand (state manager)

[Code](https://github.com/UglyGhoulChrist/quiz-nextjs-zustand.git)\
[Проект на платформе Vercel](https://quiz-nextjs-zustand.vercel.app/)

---

#### QUIZ по JavaScript 'Что будет выведено в консоль?'

##### Страницы:

- Главная: _Static Site Generation (SSG)_.
  - Карточки вопросов с вариантами ответов. По нажатию на кнопку всплывает
    модальное окно с правильным ответом и пояснением.

- Админка: _Client-side Rendering (CSR)_.
  - Форма позволяет добавлять новые вопросы.
  - Список карточек с вопросом, вариантами ответов, правильным ответом и
    пояснением. На карточке есть кнопка удаления вопроса.

##### Технологии, применённые в проекте:

- NextJS (client & server)
- PostgreSQL (on platform Vercel)
- GitFlow
- package:
  - @vercel/postgres
  - react-hook-form
  - highlight.js

[Code](https://github.com/UglyGhoulChrist/quiz-nextjs-postgresql.git)\
[Проект на платформе Vercel](https://quiz-nextjs-postgresql.vercel.app/)

---

### React

#### Rick and Morty

##### Содержит вкладки:

- Персонажи
- Локации
- Эпизоды

Загрузка информации по API. Перемещение по вкладкам происходит без перезагрузки
страницы. Подробная информация о персонаже показывается в переиспользуемом
модальном окне.

##### Технологии, применённые в проекте:

- React
- Reac-Dom
- Sass (SCSS)
- Responsive Layout (отзывчивая верстка)
- Mobile First
- БЭМ
- HTML5

[Code](https://github.com/UglyGhoulChrist/rick-and-morty-react.git)\
[GitHub Pages](https://uglyghoulchrist.github.io/rick-and-morty-react/)

---

#### Персонажи Marvel

[Доработка проекта на JavaScript](https://github.com/UglyGhoulChrist/marvel-js.git)

##### Первый проект на React:

- Персонажи Marvel загружаются из файлов.
- Для каждого персонажа создаётся модальное окно.

##### Технологии, применённые в проекте:

- React
- Reac-Dom
- CSS modules
- Sass (SCSS)
- Responsive Layout
- Mobile First
- HTML5

[Code](https://github.com/UglyGhoulChrist/marvel-react.git)\
[GitHub Pages](https://uglyghoulchrist.github.io/marvel-react/)

---

### JavaScript

#### Персонажи Marvel

Информация загружается по API. Для каждого персонажа создаётся модальное окно.

##### Технологии, применённые в проекте:

- JavaScript
- Bootstrap5
- HTML5

[Code](https://github.com/UglyGhoulChrist/marvel-js.git)\
[GitHub Pages](https://uglyghoulchrist.github.io/marvel-js/)

---

#### Календарь

Поставлена задача создать отображение одного месяца календаря для React проекта.
Если месяц начинается не с понедельника , то необходимо показать даты
предыдущего месяца в этой неделе. Аналогично, если месяц заканчивается не в
воскресенье, то неделю нужно добить датами следующего месяца.

##### Технологии, применённые в проекте:

- JavaScript

[Code](https://github.com/UglyGhoulChrist/ra16-homeworks-calendar/blob/master/src/utils/getCalendar.js)

---

### HTML, CSS

#### Сайт разработки ПО

Проект создавался по макету в Adobe Photoshop 2020

##### Технологии, применённые в проекте:

- JS
- Slick-slider
- Sass (SCSS)
- БЭМ
- Responsive Layout
- Mobile First
- Font Awesome
- HTML5

[Code](https://github.com/UglyGhoulChrist/limpon-html-css-js.git)\
[GitHub Pages](https://uglyghoulchrist.github.io/limpon-html-css-js/)

---

#### Сайт доставки еды

##### Проект создавался по макету в Figma

##### Технологии, применённые в проекте:

- HTML5
- Sass (SCSS)
- БЭМ

[Code](https://github.com/UglyGhoulChrist/healthy-food-html-css.git)\
[GitHub Pages](https://uglyghoulchrist.github.io/healthy-food-html-css/src/)

---

### Python

#### Игра в города России, пользователь против компьютера

##### Ход пользователя:

- Пользователь начинает игру, называя первый город.
- Если города нет в списке, то говорим ему, что надо назвать другой город.
- Если названный город существует, заносим его в список названных городов.
- Получаем первую букву с которой должен начинаеться следущий ход.
- Передаём ход компьютеру.

##### Ход компьютера:

- Выбираем случайным образом город из списка городов, заносим его в список
  названных городов.
- Получаем первую букву с которой должен начинаеться следущий ход.
- Передаём ход пользователю.

##### Ход игры:

- Ходы игроков выводятся на экран.
- Если городов не осталось, то пользователь выиграл.

##### Технологии, применённые в проекте:

- Базовые знания python
- Работа с файлами
- Библиотека requests (http-запросы)
- Библиотека bs4 (парсер HTML)

[Code](https://github.com/UglyGhoulChrist/city-game-python.git)

---

#### Игра «Быки и коровы»

##### Правила:

- Компьютер загадывает четырехзначное число, все цифры которого различны (первая
  цифра числа отлична от нуля).
- Игроку необходимо разгадать задуманное число.
- Игрок вводит четырехзначное число c неповторяющимися цифрами, компьютер
  сообщают о количестве «быков» и «коров» в названном числе «бык» — цифра есть в
  записи задуманного числа и стоит в той же позиции, что и в задуманном числе
  «корова» — цифра есть в записи задуманного числа, но не стоит в той же
  позиции, что и в задуманном числе.

##### Технологии, применённые в проекте:

- Базовые знания python

[Code](https://github.com/UglyGhoulChrist/bulls-and-cows-game-python.git)

---

<div id="socials" align="center">
    <h2>Связаться со мной:</h2>
</div>

<div id="socials" align="center">
    <a href="https://wa.me/79101807117" target="_blank">
        <img src="https://img.shields.io/badge/WhatsApp-blue?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
    </a>
    <a href="https://t.me/UglyGhoulChrist" target="_blank">
        <img src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
    </a>
</div>

<div id="stat" align="center">
    <h2>Моя статистика:</h2>
</div>

<div id="stat" align="center">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=UglyGhoulChrist&theme=default" alt="" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=UglyGhoulChrist&theme=default" alt="" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=UglyGhoulChrist&theme=default" alt="" />
</div>
