---
menus:
  main:
    params:
      class: center
#    parent: "Корисна інформація"
    pre: <i class="fa-solid fa-code"></i>
    weight: 3
title: "Gramps"
date: 2024-10-04T12:00:00+03:00
draft: false
url: "/gramps/"
summary: "Опис Gramps та його можливостей"
---

Gramps – це потужне генеалогічне програмне забезпечення з відкритим кодом, яке дозволяє організувати, досліджувати та зберігати родинні історії у формі родоводу. Ця стаття містить повний посібник для роботи з Gramps, що охоплює встановлення, налаштування та використання основних функцій програми.

## Огляд Gramps

[Gramps](https://gramps-project.org/) (Genealogical Research and Analysis Management Programming System) — це програмне забезпечення, створене для ведення генеалогічних досліджень. Основна мета програми — допомогти користувачам організувати великі обсяги даних про родину, досліджувати родовід, а також зберігати інформацію про події, місця та джерела.

## Встановлення та налаштування Gramps

### Завантаження та встановлення програми

1. Перейдіть на офіційний сайт [Gramps](https://gramps-project.org/blog/download/) (Gramps Project).
2. Виберіть версію для вашої операційної системи (Windows, MacOS, Linux).
3. Слідуйте інструкціям для встановлення програми. Установка проходить стандартно для кожної з операційних систем.

### Перший запуск і базові налаштування

Після встановлення:

1. Запустіть Gramps.
2. Під час першого запуску Gramps запропонує налаштувати базову конфігурацію (базу даних, мову інтерфейсу тощо).
3. Для зручної роботи виберіть українську мову через меню налаштувань (якщо необхідно).

#### Вибір мови інтерфейсу

Мову інтерфейсу можна змінити через меню:

1. Налаштування → Загальні → Мова.
2. Виберіть бажану мову та підтвердіть зміни.

#### Налаштування бази даних

Gramps працює з базами даних для зберігання інформації про родовід. При першому запуску програми потрібно створити нову базу:

1. Файл → Створити нову базу даних.
2. Вкажіть назву бази та виберіть каталог для зберігання даних.

## Сутності в Gramps

### Особи

Кожна людина, додана до вашого родоводу, є “особою” в Gramps. Всі біографічні дані, події, та відносини з іншими людьми будуть пов’язані з цією сутністю.

#### Додавання нової особи

Щоб додати нову особу:

1. Виберіть Додати особу в меню або використовуйте кнопку + на панелі інструментів.
2. Заповніть поля: ім’я, дата народження, місце народження тощо.

#### Редагування особистих даних

Редагувати дані особи можна в будь-який момент:

1. Виберіть особу у списку.
2. Натисніть Редагувати.
3. Змініть необхідні поля, наприклад, додайте нову подію або змініть наявні дані.

#### Пошук осіб

Для швидкого пошуку особи:

1. Використовуйте панель Пошук у верхній частині інтерфейсу.
2. Введіть ім’я, дату народження або інші ключові дані.

### Сім’ї

Сім’ї в Gramps відображають стосунки між особами, включаючи шлюби, діти та родичі.

#### Створення сімейних зв’язків

1. Оберіть двох осіб і створіть зв’язок через меню Сім’я → Створити сім’ю.
2. Додайте дітей або інших членів родини.

#### Приклад декількох шлюбів

Gramps дозволяє додавати кілька шлюбів для однієї особи:

1. Оберіть особу.
2. В розділі Події додайте нову подію шлюбу.

### Події

Події — це важлива частина інформації в генеалогії, що описує моменти життя осіб.

#### Додавання подій

Щоб додати подію:

1. Виберіть особу.
2. Натисніть Додати подію і оберіть тип (народження, шлюб, смерть тощо).
3. Заповніть додаткові поля (дата, місце, примітки).

#### Зв’язування подій з особами

Подію можна прив’язати до кількох осіб одночасно:

1. Вкажіть основну особу.
2. Додайте співучасників події (наприклад, свідків або членів сім’ї).

### Місця

Gramps дозволяє додавати та використовувати географічні місця для подій.

#### Додавання географічних місць

Щоб додати нове місце:

1. В меню Місця додайте новий запис з назвою, координатами, країною.
2. Використовуйте це місце для зв’язування з подіями (народження, проживання тощо).

### Сховища, джерела та цитати

Gramps надає інструменти для додавання джерел, що підтверджують генеалогічні дані.

#### Додавання джерел інформації

Щоб додати нове джерело:

1. Оберіть меню Джерела → Додати джерело.
2. Вкажіть назву джерела, автора та дату.
3. Додайте сховище де це джерело знаходиться

#### Цитування джерел

Після створення джерела його можна цитувати для підтвердження будь-якої події чи особи:

1. Відкрийте картку події.
2. В розділі Цитати додайте джерело.

### Медіа (файли)

Gramps підтримує додавання фотографій та документів, пов’язаних з особами та подіями.

Додавання медіа-файлів

Щоб додати медіа:

1. Виберіть Медіа → Додати медіа.
2. Виберіть файл на вашому комп’ютері та зв’яжіть його з подією або особою.

## Робота з деревом родоводу

### Візуалізація родинного дерева

Gramps дозволяє переглядати родовід у вигляді графічного дерева. Ви можете переміщатися по поколіннях, натискаючи на окремі гілки, а також змінювати візуалізацію за допомогою фільтрів.

### Навігація по родинних зв’язках

Навігація між особами в дереві дозволяє швидко пересуватися між поколіннями та бачити пов’язані події.

### Редагування та оновлення інформації

Редагувати дані можна прямо через дерево, натискаючи на особу або подію.

## Налаштування та використання звітів

### Генерація звітів та діаграм

Gramps має можливість генерувати різноманітні звіти, такі як текстові родоводи, хронології подій або діаграми сімейних відносин.

### Налаштування параметрів звітів

Звіти можна налаштувати за допомогою вбудованого редактора параметрів, вибираючи які саме дані включати до звіту.

### Експорт звітів в різні формати

Звіти можна експортувати в PDF, DOC, ODT або текстові файли для подальшого друку чи обміну.

## Імпорт та експорт даних

### Використання формату GEDCOM

Формат GEDCOM є стандартом для обміну генеалогічними даними. Ви можете імпортувати інформацію з інших програм або експортувати свій родовід.

### Імпорт даних з інших програм

Gramps підтримує імпорт з інших генеалогічних програм через формат GEDCOM, а також має спеціальні плагіни для деяких платформ.

### Експорт родинного дерева

Для збереження або передачі даних іншим користувачам ви можете експортувати родовід у формат GEDCOM або інші підтримувані формати.

## Розширені функції Gramps

### Фільтри та пошукові запити

Gramps має розширені функції фільтрації та пошуку, що дозволяють сортувати дані за складними критеріями, такими як дати, місця або стосунки.

### Користувацькі звіти та діаграми

Gramps дозволяє налаштовувати власні шаблони звітів, що дає можливість створювати специфічні звіти для різних потреб.

### Теги та категорії

Для кращої організації даних можна використовувати теги та категорії, що дозволяє швидко знаходити важливі події чи осіб.

## Співпраця та обмін даними

### Спільна робота над родоводом

Gramps підтримує спільну роботу над родоводом, що дозволяє кільком користувачам редагувати одну базу даних.

### Використання Gramps Web для співпраці

Gramps Web дозволяє працювати над родоводом онлайн, що спрощує співпрацю між користувачами.

## Інтеграція з онлайн-сервісами

Gramps дозволяє підключатися до генеалогічних баз даних для імпорту інформації про родичів.

### Підключення до генеалогічних баз даних

Gramps підтримує інтеграцію з базами даних, такими як FamilySearch, що дозволяє автоматично оновлювати дані в вашому родоводі.

### Синхронізація даних

Інформація може бути синхронізована з онлайн-ресурсами, забезпечуючи актуальність даних.

## Управління великими родоводами

### Оптимізація продуктивності

Для великих родоводів важливо правильно організувати дані і використовувати фільтри для покращення продуктивності.

### Організація інформації

Використання тегів та категорій допомагає структурувати великі родоводи для легшої навігації та пошуку.

## Робота з конфліктною інформацією

### Вирішення суперечливих даних

Gramps дозволяє документувати різні джерела даних і відзначати суперечливі факти.

### Використання приміток та коментарів

Для кожного запису можна додавати примітки і коментарі, пояснюючи, чому обрано одну версію даних замість іншої.

## Налаштування конфіденційності та безпеки

### Захист персональних даних

Gramps має функції для налаштування видимості даних та обмеження доступу до особистої інформації.

### Резервне копіювання та відновлення

Програма надає інструменти для регулярного резервного копіювання бази даних, щоб уникнути втрати даних.

## Користувацькі налаштування та інтерфейс

### Персоналізація інтерфейсу

Gramps дозволяє налаштовувати інтерфейс відповідно до ваших потреб, змінюючи панелі інструментів та теми оформлення.

### Використання тем та мовних пакетів

Програма підтримує різні теми та мовні пакети, що дозволяє змінювати вигляд програми та налаштовувати її під свої потреби.

## Поради та трюки

### Швидкі клавіші та поєднання

Використання гарячих клавіш допоможе пришвидшити роботу з програмою. Наприклад, натискання Ctrl + F відкриє швидкий пошук.

### Часті помилки та як їх уникнути

Gramps має вбудовані підказки для уникнення поширених помилок, таких як дублювання осіб або некоректні дати.

## Спільнота та підтримка

### Форуми та групи користувачів

Gramps має активну спільноту користувачів, де ви можете обмінюватися досвідом і отримувати підтримку. Форуми та групи обговорень доступні на офіційному сайті.

### Внесок у розвиток Gramps

Gramps є відкритим проектом, і кожен може долучитися до його розвитку, вносячи зміни в код або перекладаючи інтерфейс на нові мови.

## Gramps Web

Gramps Web – це веб-версія Gramps, що дозволяє працювати над родоводом через браузер, не встановлюючи програму на комп’ютер.

## Gramps Web Hub

Gramps Web Hub – це централізована платформа для спільної роботи над родоводами. Вона дозволяє кільком користувачам одночасно працювати з базою даних та обмінюватися інформацією.