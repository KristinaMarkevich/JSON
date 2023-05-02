# JSON
Learning how to use GitHub
<hr>


**1. Создать внешний репозиторий с названием JSON**

**2.Клонировать репозиторий JSON на локальный компьютер**
```
$ git clone git@github.com:KristinaMarkevich/JSON.git
```
**3.Внутри локального JSON создать файл “new.json”**
```
$ touch  new.json
```
**4.Добавить файл под гит**
```
$ git add new.json
```
**5. Закоммитить файл**
```
$ git commit -m "new.json"
```
**6. Отправить файл на внешний GitHub репозиторий**
```
$ git push
```
**7. Отредактировать содержание файла “new.json” - написать информацию о себе**
```
$ cat > new.json
{
"Surname" : "Markevich",
"Name" : "Kristina",
 "Age" : 25,
  "Cat": 1,
 "Future wanted salary" : 400
}
```
**8. Отправить изменения на внешний репозиторий**
```
$ git add new.json
$ git commit -m "new.json"
$ git push
```
**9. Создать файл preferences.json**
```
$ touch preferences.json
```
**10.  В файл preferences.json” добавить информацию о своих предпочтениях**
```
$ cat > preferences.json
{
  "preferences": 
  { "movie" : "Titanic",
"TV-Show" : "Breaking bad",
"food" : "ramen",
"season" : "summer",
"country i'd like to visit" : "Japan" }
} 
```
**11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**
```
$ cat > skills.json
{ 
  "skills" : ["termimal", "SQL", "postman", "creating bug reports"]
}
```
**12. Сделать коммит в одну строку**
```
$ git commit -a -m "add preferences.json and skills.json "

```
**13. Отправить сразу 2 файла на внешний репозиторий**
```
$ git push
```
 **14. На веб интерфейсе создать файл [bug_report.json](https://github.com/KristinaMarkevich/JSON/blob/main/bug_report.json)**
 
 **15. Сделать Commit changes (сохранить) изменения на веб интерфейсе**
 
 **16. На веб интерфейсе модифицировать файл [bug_report.json](https://github.com/KristinaMarkevich/JSON/blob/main/bug_report.json), добавить баг репорт в формате JSON**
 
 **17. Сделать Commit changes (сохранить) изменения на веб интерфейсе**
 
 **18. Синхронизировать внешний и локальный репозиторий JSON**
 ```
$ git pull
```


