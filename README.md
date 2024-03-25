# new-project

https://github.com/svital73/new-project.git

Створіть в своєму середовищі новий каталог з назвою "new-project".
Перейдіть до каталогу "new-project".
Ініціалізуйте новий публічний Git-репозиторій всередині каталогу "new-project".


git init

git add README.md

git commit -m "init"

git branch -M main

git remote add origin https://github.com/svital73/new-project.git

git push -u origin main 


Створіть нову гілку з назвою "development" і перейдіть до неї.

git checkout -b development

git commit -am "1 commit for branch development"

git push -u origin main



git checkout main

git branch

git merge development

