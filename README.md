 4. Создать внешний репозиторий c названием JSON.

Создал

 5. Клонировать репозиторий JSON на локальный компьютер.

git clone https://github.com/sbrownbear/JSON.git

 6. Внутри локального JSON создать файл “new.json”.

touch new.json

 7. Добавить файл под гит.

git add new.json

 8. Закоммитить файл.

git commit -m 'creat file'

 9. Отправить файл на внешний GitHub репозиторий.
git push

 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в 
формате JSON.

vim new.json
i
esc
:wq

 11. Отправить изменения на внешний репозиторий.

git commit -am 'modified'
git push

 12. Создать файл preferences.json

touch preferences.json

 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

vim preference.json
i
esc
:wq

 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

vim skills.json
i
esc
:wq

 15. Отправить сразу 2 файла на внешний репозиторий.

git add.
git commit -m 'creat file'
git push

 16. На веб интерфейсе создать файл bug_report.json.

edit new file

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

commit file

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

edit this file

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

commit this file

 20. Синхронизировать внешний и локальный репозиторий JSON

git pull
