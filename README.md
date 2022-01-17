# MyGitHelp
----------------
Установка git
git remote set-url origin https://<githubtoken>@github.com/<username>/<repositoryname>.git
git remote set-url origin https://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@github.com/leo6255/MyGitHelp.git
git init - инициализация проекта. Предварительно нужно перейти в папку проекта(при этом создается скрытая папка .git).

если ругается на сертификат, то есть ssl определяет, что кто-то перехватывает ваш трафик, можно отключить проверку, добавив в файл .git/config
[http]
	sslVerify = false
	
git remote -v - посмотреть адреса для чтения и записи, привязанные к репозиторию
----------------

Добавление файлов
git add <file>  - добавить файл в проект, за которым гит будет следить
git add .  - добавить в проект все файлы из папки
git commit -m "описание" - фиксирует проект
git push - отправить изменения на гит
  
Работа с ветками  
git brunch - посмотреть на какой ветке сейчас находимся
git brunch test - создать ветку test
git brunch -D test - удалить ветку test
git checkout test - перейти в ветку test
