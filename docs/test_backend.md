## Backend developer (Node.js)

1. Встановлення необхідних інструментів
  - [node.js](https://nodejs.org/en/)
  - [postman](https://www.postman.com/)

2. Тестове завдання
  - Запустити http-сервер (на порті 8181).
  - Створити 3 ендпойнти:
    - [POST] /users - створення юзера
    - [GET] /users - отримати всіх створених юзерів
    - [GET] /users/:userId - отримати юзера по його ід
  - Протестувати.
  - Залити проект на GitHub.

  Модель юзера:
  - id - генерується автоматично. Можна використати пакет uuid або реалізувати самостійно.
  - userName - стрінга, більше 1 символа, менше 25, дозволені тільки англ. букви
  - email - емейл користувача, валідація на коректний формат

  P.S: Для написання проекту можна використати довільний фреймворк - express.js, nest.js, fastify, hapi…..

3. Опублікувати результати

Як закінчиш з тестовим завданям, необхідно опублікувати його на [github.com](http://github.com/)

Залишилося найпростіше, використовуючи інструмент git, додати результати своєї роботи за допомогою PullRequest на наш скромний сайт, як тільки ти зробиш PR в такому ж форматі, як показано нижче, ми подивимося результати твоєї роботи і приступимо до наступних кроків.

Список тих, хто зробив тестове:
```markdown
1) Misha Xodanych (nixage)
FB: https://www.facebook.com/profile.php?id=100009308260522;
GH: https://github.com/nixage/crutch-and-rake/tree/master
```
```markdown
2) Mark Zavatskyi
FB: https://www.facebook.com/profile.php?id=100017184282013
GH: https://github.com/ffmz1904/main/tree/mz-usersApi
```
```markdown
3) Kolya Vizenko
FB: https://www.facebook.com/profile.php?id=100023301580189
GH: https://github.com/KolyaViz/C-and-R-Uzh-test
```
```markdown
4) Kolya Khudyk
FB: https://www.facebook.com/kolya.khuduk.3
GH: https://github.com/kolya511/crutch-and-rake
```
Приклад тих даних, які треба внести за допомогою pullrequest на цю сторінку (лінк на репозиторій [ось тут](https://github.com/Crutch-and-Rake-Uzhhorod/main))

```markdown
name/nikename: Ivan
link to FB/LinkedIn: facebook.com/brusd
link to my test task repository: ...
```
