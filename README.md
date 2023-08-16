# Памятка Git + Github 

## Проверка на .git 

`$ ls -la`

## инициализация git 

`$ git init`

## в случае ошибки папки, удаляем .git

`$ rm -rf . git/`

## Индексация файлов перед коммитом 

`$ git add.`

## Проверить статус репозитория

`$ git status`

## Сохраняем изменения в истории git

`$ git commit -m "Commit description"`

## Посмотреть историю коммитов 

`$ git log`

## Проверить git пользователя

`$ git config --list | grep user `

## Изменить пользователя git

`$ git config --global user.name "Mikhai Prokopov"`
`$ git config --global user.email prokopovmisha94@gmail.com`

## Проверить наличие удаленного репозитория (Github)

`$ git remote show origin`

## Можно удалить origin

`$ git remote rm origin`

## Добавить удалённый репозиторий 

`$ git remote add origin https://github.com/Seemad94/position-git.git`

## Отправляем коммиты на Github

`$ git push origin master`

## При первом скачивании проекта с GIthub делаем его клон

`$ git clone https://github.com/Seemad94/landing.git`

## Переходим в папку repository_name

`$ cd repository_name`

## Открываем папку в VS Code

`$ code .`

## Для скачивания обновлений с Github в уже существующий репозиторий 

`$ git pull origin main`

## В случае ошибки push можно использовать флаг --force

`$ git push pages master --force`