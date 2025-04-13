**README – Документація **

**функціонального **

**рішенняВерсія чат гпт**

**Зміст**

 Вступ

 Користувацькі ролі

 Огляд сайту та навігаційна структура

 Функціональні вимоги за типами сторінок

1. Волонтер

1.1. Головна сторінка

1.2. Пошук тварини

1.3. Сторінка тварини

1.4. Форма отримання тварини

1.5. Сторінка передачі тварини

1.6. Inbox

1.7. Налаштування профілю

1.8. Список вибраних оголошень

2. Притулок

2.1. Головна сторінка \(схожа на YouTube Studio\) 2.2. Мої оголошення

2.3. Створити оголошення про тваринку

2.4. Налаштування профілю

2.5. Inbox

3. Сторінки статей комʼюніті

3.1. Створити статтю \(новину/блог/розіграш\) README  Документація функціонального рішенняВерсія чат гпт

1

3.2. Створити Pet Stories 4. Загальні сторінки

4.1. Сторінка реєстрації

4.2. Сторінка інформації про притулок

4.3. Сторінка інформації про волонтера

 Логіка взаємодії та стани інтерфейсу

 Перехід між режимами \(рольова динаміка\) **Вступ**

Цей документ описує функціональне рішення для створення клікабельного 

прототипу платформи, спрямованої на допомогу безпритульним тваринам 

в сучасних реаліях війни. Платформа охоплює два основних напрямки: **Волонтери** – користувачі, які шукають оголошення, беруть участь у 

передачі тварин, залишають власні історії \(Pet Stories\) та спілкуються 

через систему повідомлень. 

**Притулки** – організації, що створюють оголошення про тварин, керують 

своїм контентом, отримують запити та обробляють повідомлення. 

Разом із цим сайт містить спільний комʼюніті-контент \(новини, блоги, розіграші\) доступний усім користувачам \(включаючи гостей\). 

**Користувацькі ролі**

**Гості** – користувачі, які не увійшли в систему. Вони можуть переглядати 

публічний контент \(новини, блоги, Pet Stories тощо\). 

**Волонтери** – користувачі, які бажають брати участь у передачі тварин 

або допомагати через платформу. Функціональні можливості: Функції отримання та передачі тварин за рахунок притулків, Збереження та перегляд улюблених оголошень, Написання власних Pet Stories, 

Взаємодія з іншими волонтерами або притулками, Можливість донатів для окремих тварин або притулків, README  Документація функціонального рішенняВерсія чат гпт

2

Створення відгуків про притулки. 

**Притулки** – організації, що розміщують оголошення про тварин та 

ведуть своє інформаційне поле:

Створення та управління оголошеннями та статтями, Отримання тварин від волонтерів, 

Популяризація свого притулку за допомогою рейтингових систем 

сайту, 

Налаштування профілю \(контакти, опис, тип закладу\). 

**Огляд сайту та навігаційна структура**

Платформа реалізована як єдиний сайт із спільною головною сторінкою, яка демонструє комʼюніті-контент, а також персоналізованими особистими 

кабінетами з відповідним функціоналом. 

**Головна сторінка:** Відображає загальний контент: новини, блоги, Pet Stories, розіграші, а також віджети як «Рекомендовані тварини», «Наші 

тваринки» та інше. 

**Персональний кабінет:** Після авторизації користувача \(волонтера або 

притулку\) інтерфейс адаптується до його ролі за допомогою 

динамічного меню або окремих секцій. 

**Спільні елементи:** Хедер \(з логотипом, пошуком, Inbox та профілем\) та 

футер із загальною інформацією \(контакти, соціальні мережі, умови 

використання тощо\). 

**Функціональні вимоги за типами сторінок**

**1. Волонтер**

**1.1. Головна сторінка волонтера**

**Хедер:**

Емблема сайту. 

Пошуковий блок. 

Кнопка **"Створити" ** з випадаючим меню: README  Документація функціонального рішенняВерсія чат гпт

3

"Оголошення передачі". 

"Pet Stories". 

Кнопка/іконка **Inbox**. 

Кнопка/іконка **Профіль**. 

Під хедером навігаційна частина \(на усіх сторінках, окрім головної\) **Головна область:**

**Відображення контенту комʼюніті**

**Рекомендовані тварини** – блок із актуальними оголошеннями. 

**Вибране** – додатковий блок із вибраними тваринами. 

**Історія переглядів** – візуальний блок, який демонструє історію 

активності користувача. 

**1.2. Пошук тварини**

**Картка оголошення:** На ній вказано: Дані тваринки

Назва притулку

Кнопка/іконка “Зберегтиˮ

Кнопка “Детальнішеˮ 

**Фільтри:** Можливість відфільтрувати оголошення за категоріями \(вид 

тварини, вік, стан здоровʼя, місцезнаходження тощо\). 

Якщо оголошень немає або надані варіанти не підходять — кнопка для 

подання запиту з переходом до відповідної форми. 

**1.3. Сторінка для тварини**

Можливість перейти на профіль притулку. 

Кнопка для донату тварині. 

Форма для взяття тварини. 

**1.4. Сторінка форми на отримання тварини**

Обовʼязкові поля: **email**, **Ім'я та Прізвище**, **Контактний номер**, **Місцезнаходження**. 

README  Документація функціонального рішенняВерсія чат гпт

4

Поле для примітки, щоб додати додаткове повідомлення. 

**1.5. Сторінка віддати тваринку в хороші руки**

**Картка оголошення:** всі дані тваринки

Функціонал пошуку для знаходження потрібного оголошення. 

**1.6. Inbox**

Система повідомлень. 

**1.7. Налаштування профілю \(волонтер\)** Відображення інформації: **email**, **Ім'я та Прізвище**, **Контактний номер**, **Місцезнаходження**. 

Можливість редагування даних. 

**1.8. Список вибраних оголошень**

Перелік оголошень, позначених як улюблені волонтером. 

**2. Притулок**

**2.1. Головна сторінка притулку**

**Хедер:**

Емблема сайту. 

Пошук. 

Кнопка **"Створити" ** з підменю:

"Оголошення передачі". 

"Статтю". 

Кнопка/іконка **Inbox**. 

Кнопка/іконка **Профіль**. 

**Головна область:**

Відображення спільного контенту \(новини, блог, Pet Stories, розіграші\). 

**2.2. Мої оголошення**

README  Документація функціонального рішенняВерсія чат гпт

5

Список оголошень з оглядовими картками. 

Таблиця з інформацією: кількість відвідувань, переглядів, лайків, дата 

публікації. 

Кнопки для редагування та видалення оголошення. 

**2.3. Створити оголошення про тваринку**

Форма для введення даних:

Обовʼязкові поля: **Фото тварини**, **Вид тварини**, **Порода**, **Ім'я**, **Вік**, **Стать**, **Стан здоров'я**, **Додатковий опис**. 

**2.4. Налаштування профілю \(притулку\)** Інформація про заклад:

**Назва закладу**, **Тип закладу**, **Контактний телефон**, **Локація**, **Короткий опис**. 

Параметр прийому тварин \(чи приймає, чи ні\). 

**2.5. Inbox \(притулку\)**

Приклади повідомлень:

Запит на передачу тваринки. 

Повідомлення про те, що донат отримано від волонтера. 

Сповіщення, що притулок набув популярності. 

Опціонально\) Запит на взяття тваринки волонтером. 

Опціонально\) Повідомлення про реакції на статті \(новини, блоги\). 

**3. Сторінки статей комʼюніті**

**3.1. Створити статтю \(новину/блог/розіграш\)** Інтерфейс для написання та форматування тексту, Можливість додавання зображень, 

Попередній перегляд. 

**3.2. Створити Pet Stories**

README  Документація функціонального рішенняВерсія чат гпт

6

Те саме що й Створити статтю

**4. Загальні сторінки**

**4.1. Сторінка реєстрації**

Роздільна панель або вкладки:

**Вкладка "Волонтер" **: специфічні поля — **Ім'я та Прізвище**, **Контактний номер**, **Місцезнаходження**. 

**Вкладка "Притулок" **: специфічні поля — **Назва закладу**, **Тип **

**закладу**, **Контактний телефон**, **Локація**, **Короткий опис**, завантаження документів \(опціонально\). 

Спільний набір полів: **email**, **Пароль** та **Підтвердження пароля**. 

Реєстрація через соцмережі. 

Посилання на «Умови користування» та «Політику конфіденційності». 

**4.2. Сторінка інформації про притулок**

Детальна інформація про заклад. 

Можливість написати повідомлення до притулку. 

Кнопки для передачі знайденої тварини або донату. 

Відображення оголошень тварин, огляди, відгуки. 

**4.3. Сторінка інформації про волонтера**

Детальна інформація про користувача \(email, **Ім'я та Прізвище**, **Контактний номер**, **Місцезнаходження**\). 

Кнопка для написання повідомлення. 

**Логіка взаємодії та стани інтерфейсу**

**Стан завантаження:** Індикатори завантаження при переході між 

сторінками або завантаженні даних. 

**Валідація форм:** Реактивна перевірка полів, повідомлення про помилки 

у реальному часі. 

README  Документація функціонального рішенняВерсія чат гпт

7

**Повідомлення про успіх/помилку:** Після відправки форм 

відображаються повідомлення з підтвердженням або вказівкою на 

помилки. 

**Інтерактивні модальні вікна:** Наприклад, для підтвердження донату, перегляду деталей звернень тощо. 

**Перехід між режимами**

**Рольова динаміка:**

Після входу в систему визначається роль користувача і відповідно 

формується меню особистого кабінету. 

Волонтер бачить секції: «Передати тваринку», «Отримати 

тваринку», «Написати Pet Stories», «Збережені оголошення» тощо. 

Притулок бачить секції: «Мої оголошення» та статистика для них, 

«Створити статтю» тощо. 

**Єдина точка входу:**

Головна сторінка з комʼюніті-контентом доступна всім, а після 

автентифікації користувач переходить на персоналізовану панель із 

чітким розділенням функціоналу. 

README  Документація функціонального рішенняВерсія чат гпт

8



