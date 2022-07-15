1. Создать внешний репозиторий c названием JSON.

`New`

 2. Клонировать репозиторий JSON на локальный компьютер.

`git clone https://github.com/sbrownbear/JSON.git`

 3. Внутри локального JSON создать файл “new.json”.

`touch new.json`

 4. Добавить файл под гит.

`git add new.json`

 5. Закоммитить файл.

`git commit -m 'creat file'`

 6. Отправить файл на внешний GitHub репозиторий.

`git push`

 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в 
формате JSON.

<<<<<<< HEAD
`vim new.json`, 
`i`,
`esc`,
=======
`vim new.json`
`i`
`esc`
>>>>>>> 4ed9a1f206bf1383408ee2f403d279ce14d2eea2
`:wq`

 8. Отправить изменения на внешний репозиторий.

<<<<<<< HEAD
`git commit -am 'modified'`,
=======
`git commit -am 'modified'`
>>>>>>> 4ed9a1f206bf1383408ee2f403d279ce14d2eea2
`git push`

 9. Создать файл preferences.json

`touch preferences.json`

 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

<<<<<<< HEAD
`vim preference.json`,
`i`,
`esc`,
=======
`vim preference.json`
`i`
`esc`
>>>>>>> 4ed9a1f206bf1383408ee2f403d279ce14d2eea2
`:wq`

 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

<<<<<<< HEAD
`vim skills.json`,
`i`,
`esc`,
=======
`vim skills.json`
`i`
`esc`
>>>>>>> 4ed9a1f206bf1383408ee2f403d279ce14d2eea2
`:wq`

 12. Отправить сразу 2 файла на внешний репозиторий.

<<<<<<< HEAD
`git add.`,
`git commit -m 'creat file'`,
=======
`git add.`
`git commit -m 'creat file'`
>>>>>>> 4ed9a1f206bf1383408ee2f403d279ce14d2eea2
`git push`

 13. На веб интерфейсе создать файл bug_report.json.

`edit new file`

 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

`commit file`

 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

`edit this file`

 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

`commit this file`

 17. Синхронизировать внешний и локальный репозиторий JSON

`git pull`
