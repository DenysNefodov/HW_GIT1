# HW_GIT1

**JSON**
***
**Создать внешний репозиторий c названием JSON / ветку с названием JSON**
```Bash
git branch JSON
git checkout JSON
```
**Внутри локального JSON создать файл “new.json”**
```Bash
touch new.json
```
**Добавить файл под гит**
```Bash
git add new.json
```
**Закоммитить файл**
```Bash
git commit -m "create file new.json"
```
**Отправить файл на внешний BashHub репозиторий**
```Bash
git push -u origin JSON
```
**Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.**
```JSON
{
    "First Name":"Denys",
    "Second Name": "Nefodov",
    "Count home animals": 1,
    "Salary": 5000
}
```
**Отправить изменения на внешний репозиторий**
```Bash
git commit -am "fix file new.json"
git push -u origin JSON
```
**Создать файл preferences.json**
```Bash
touch file preferences.json
```
**В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.**
```JSON
{
    "Favorite film":"The Lord of the Rings",
    "Favorite serial":"Game of Thrones",
    "Favorite food":"Seafood",
    "Favorite time of year": "Summer",
    "Favorite country": "Italy"
}
```
**Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**
```Bash
touch file skills.json
```
```JSON
{
    "Skills_1":"GIT",
    "Skills_2": "SQL",
    "Skills_3":"Terminal Linux",
    "Skills_4":"VIM redactor",
    "Skills_5":"JavaScript",
    "Skills_6":"Postman",
    "Skills_7":"Theory of Testing"
}
```
**Отправить сразу 2 файла на внешний репозиторий.**
```Bash
git add .
git commit -m "create two file preferences.json & skills.json and insert in this file information from my favorite preferences and my skills"
git push -u origin JSON
```
**На веб интерфейсе создать файл bug_report.json.**
```Bash
Create on the web interface file "bug_report.json"
```
**Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
```Bash
Commit on the wev interface "Create file bug_report.json"
```
**На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.**
```Bash
Added bug report in format JSON in the file bug_report.json
```
**Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
```Bash
Create commit on the web interface
```
**Синхронизировать внешний и локальный репозиторий JSON**
```Bash
git pull origin JSON:JSON
```

**XML**
***
**Создать внешний репозиторий c названием XML / ветку с названием XML**
```Bash
git checkout -b XML
```
**Внутри локального XML создать файл “new.xml”.**
```Bash
touch new.xml
```
**Добавить файл под гит.**
```Bash
git add new.xml
```
**Закоммитить файл.**
```Bash
git commit -m "create file new.xml"
```
**Отправить файл на внешний BashHub репозиторий.**
```Bash
git push -u origin XML
```
**Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.**
```XML
<?xml version = "1.0"?>
<contact-info>
    <name>Nefodov Denys</name>
    <animals>1</animals>
    <salary>1000$</salary>
</contact-info>
```
**Отправить изменения на внешний репозиторий.**
```Bash
git commit -am "add information in format XML from myself"
git push -u origin XML
```
**Создать файл preferences.xml**
```Bash
touch preferences.xml
```
**В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.**
```XML
<?xml version = "1.0"?>
<preferences>
    <film>The Lord of the Rings</film>
    <serial>Game of Thrones</serial>
    <food>Seafood</food>
    <time>summer</time>
    <country>Italy</country>
</preferences>
```
**Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML**
```Bash
touch skills.xml
```
```XML
<?xml version = "1.0"?>
<skills>
    <skills1>GIT</skills1>
    <skills2>SQL</skills2>
    <skills3>Terminal Linux</skills3>
    <skills4>VIM redactor</skills4>
    <skills5>JavaScript</skills5>
    <skills6>Postman</skills6>
    <skills7>Theory of Testing</skills7>
</skills>
```
**Сделать коммит в одну строку.**
```Bash
git add .
git commit -m "create two file preferences.xml & skills.xml and insert in this file information from my favorite preferences and my skills in XML format"
```
**Отправить сразу 2 файла на внешний репозиторий.**
```Bash
git push -u origin XML
```
**На веб интерфейсе создать файл bug_report.xml.**
```Bash
Create on the web interface file "bug_report.xml"
```
**Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
```Bash
Commit on the wev interface "Create file bug_report.xml"
```
**На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.**
```Bash
Added bug report in format XML in the file bug_report.XML
```
**Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
```Bash
Create commit on the web interface
```
**Синхронизировать внешний и локальный репозиторий XML**
```Bash
git pull origin XML:XML
```

**TXT**
***
**Создать внешний репозиторий c названием TXT / ветку с названием TXT**
```Bash
git checkout -b TXT
```
**Внутри локального TXT создать файл “new.txt”.**
```Bash
touch new.txt
```
**Добавить файл под гит.**
```Bash
git add new.txt
```
**Закоммитить файл.**
```Bash
git commit -m "create file new.txt"
```
**Отправить файл на внешний BashHub репозиторий.**
```Bash
git push -u origin TXT
```
**Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.**
```TXT
1. Nefodov Denys Valentinovich;
2. Animals - 1;
3. Salary - 5000;
```
**Отправить изменения на внешний репозиторий.**
```Bash
git push -u origin TXT
```
**Создать файл preferences.txt**
```Bash
touch preferences.txt
```
**В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.**
```TXT
1. Film - The Lord of the Rings;
2. Serial - Game of Thrones;
3. Time of year - Summer;
4. Food - Seafood;
5. Country - Italy;
```
**Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT**
```Bash
touch skills.txt
```
```TXT
Skills

1. GIT;
2. Terminal Linux;
3. SQL;
4. VIM;
5. JavaScript;
6. Postman;
7. Testing Theory;
```
**Сделать коммит в одну строку.**
```Bash
git add .
git commit -m "create two file preferences.txt & skills.txt and insert in this file information from my favorite preferences and my skills in TXT format"
```
**Отправить сразу 2 файла на внешний репозиторий.**
```Bash
git push -u origin TXT
```
**На веб интерфейсе создать файл bug_report.txt.**
```Bash
Create on the web interface file "bug_report.txt"
```
**Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
```Bash
Commit on the wev interface "Create file bug_report.xml"
```
**На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.**
```Bash
Added bug report in format TXT in the file bug_report.txt
```
**Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
```Bash
Create commit on the web interface
```
**Синхронизировать внешний и локальный репозиторий TXT**
```Bash
git pull origin TXT:TXT
```
