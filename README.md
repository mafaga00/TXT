# TXT

 1. Создать внешний репозиторий c названием TXT.
 ***
 `Repositories -> New -> Repos Name:TXT`
 ***
 2. Клонировать репозиторий TXT на локальный компьютер.
***
 `git clone <HTTPS link>`
***
 3. Внутри локального TXT создать файл “new.txt”.
***
`touch new.txt`
***
 4. Добавить файл под гит.
***
`git add new.txt`
***
 5. Закоммитить файл.
***
`git commit -m "add txt"`
***
 6. Отправить файл на внешний GitHub репозиторий.
***
`git push`
***
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
***
`vim new.txt -> INSERT -> esc -> :wq`

Содержание добавленной информации:
```
FIO - Ovsyannikov Nikita Dmitrievich
AGE - 22
Number of pets - 0
Future desired salary - 500
```
***
 8. Отправить изменения на внешний репозиторий.
***
`git commit -am "edit txt" -> git push`
***
 9. Создать файл preferences.txt
***
`touch preferences.txt`
***
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
***
`vim preferences.txt -> INSERT -> esc -> :wq`

Содержание добавленной информации:
```
Favorite movie - There will be blood,
Favorite series - Breaking bad,
favorite food - Steak,
favorite time of year - Winter,
country you'd like to visit - China.
```
***
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
***
`cat > skills.txt -> ^C`

Содержание добавленной информации:
```
Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
Что такое клиент-серверная архитектура.
HTTP Методы запросов на сервер.
Коды ответов HTTP сервера.
Структуры HTTP запросов и ответов.
Что такое JSON, XML. Их структура.
Тестирование API через Postman (JS, автотесты API).
Снятие и чтение логов c внешнего сервера.
Снифинг http web трафика через Charles и Fiddler.
Dev Tools веб браузеров (Google Chrome, FireFox).
VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
Мобильное тестирование.
Особенность iOS, Android, гайдлайны.
Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
Сборка Android приложений на Android Studio.
ADB (управление андройд девайсами).
Настройка прокси и vpn на iOS и Android.
Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
Основы bash скриптинг, автоматизация рутинных задач на сервере.
Доступ к удалённым серверам.
Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
База данных Postgres (установка, настройка и использование).
Нереляционная база данных Redis (установка, настройка и использование).
Нагрузочное тестирование в Jmeter.
Методология разработки Scrum.
Python. (Изучение основ. Создание клиент серверного приложения)
```
***
 12. Сделать коммит в одну строку.
***
`git add . && git commit -am "add skills"`
***
 13. Отправить сразу 2 файла на внешний репозиторий.
***
`git push`
***
 14. На веб интерфейсе создать файл bug_report.txt.
***
`Add file -> Create new file -> Name: bug_report.txt`
***
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
***
`Commit New File`
***
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
***
`Choose bug_report.xml -> Edit this file`

Содержание добавленной информации:
```
"ID"
"Title(краткое описание)"    основной
"Description(Подробное описание)"
"Req id(id требованияя)"
"Steps To Rreproduce(шаги)"      основной
"Actual Results(фактический результат)"    основной
"Expected Results(ожидаемый результат)"    основной
"Severity(важность)"
"Priority(срочность)"
"Attachments(приложение,скриншот,видео,лог)"
"Workaround(возможность обойти баг)"
"Status"
```
***
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
***
`Commit changes`
***
 18. Синхронизировать внешний и локальный репозиторий TXT
***
`git pull`
***
