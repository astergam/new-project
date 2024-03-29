Завдання 2

Опис:
Виконання другого завдання на Prometheus

Інструкція:
1. Створити новий каталог з назвою "new-project"
mkdir new-project
2. Перейдіть до каталогу "new-project"
cd new-project
3. Ініціалізувати новий публічний git-репозиторій всередині каталогу new-project
git init
4. Створити файл з назвою README.md
touch README.md
5. Підготуйте файл "README.md" до коміту
git add README.md
6. Закомітьте зміни у репозиторій з коміт повідомленням “init”
git commit -m init
7. Створіть нову гілку з назвою "development" і перейдіть до неї
git checkout -b development
8. Додайте інструкцію до файлу "README.md" і підготуйте їх до коміту
git add README.md
9. Закомітьте зміни у гілці "development" з повідомленням про коміт
git commit -m "Додано інструкцію до README.md"
10. Об'єднайте зміни з гілки "development" у гілку "main".
git checkout master
git merge development
11. Перевірте статус, переконайтеся, що все актуально
git status
12. Закомітьте зміни
git commit -m "merge development and master"
13. Відправити зміни локального репозиторія на сервер github
git push master
