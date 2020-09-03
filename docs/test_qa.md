## QA C&R

Створити публічну Trello борду, де для кожного завдання створити окрему карточку.  Лiнку на борду додати до [таблиці](https://docs.google.com/spreadsheets/d/1ghGfB5cJ5V9pxSS9PQR4LqBT0-dLNp6twpiAGR3Zem4/edit?usp=sharing).

1. Система повинна приймати тільки позитивні парні значення. Поведінка [тут](https://drive.google.com/file/d/1HtU0C4bDj1tX_kztH43KjsMxsEdmc_4p/view?usp=sharing).
    - Яке / які значення потрібно ввести для забезпечення statement coverage
    - Яке / які значення потрібно ввести для забезпечення decision coverage.

2. Система вразлива до Clickjacking. Приклад в цьому [html файлі](https://drive.google.com/file/d/1Quf7AgSlPKgq0ROtVGJlyr-0O-rzMt4E/view?usp=sharing).

    Заведіть на це баг, який б мав усю необхідну інформацію для того, щоб його могли пріоритезувати та виправити.

3. Система має інтеграцію зі Stripe для обробки платежів по картам Visa та Mastercard. Напишіть тест кейс в форматі BDD, який б перевіряв можливість їх використання

    (Використайте Scenario Outline та Testing Cards  https://stripe.com/docs/testing#cards)

4. Вам потрібно поревьювити вимоги сайта притулку для тварин, щоб знайти вузькі місця. 

    Декомпозуйте вимоги, придумавши основні фічі, які потрібні такому сайту. Завданні оформити як Mind Map.

5. Система дозволяє дивитись відео в наступних розширеннях: 1920x1200, 1920x1080, 1280x720, 640x480. 

    Скільки тест кейсів необхідно розробити, використовуючи класи еквівалентності?

6. Знайдіть 8 відмінностей (оформити як скріншот

    https://drive.google.com/file/d/1d6bnR2zjFG208hSzgOYWO5-xEhzTwyDA/view?usp=sharing
