# ***Работа с удалёнными репозиториями***

# 1. Создать аккаунт на GitHub
Перейти на [сайт](https://github.com) и нажать Sign Up.
Ввести требуемые данные и нажать *создать аккаунт*
# 2. Создать локальный репозиторий

Для этого - создать папку и указать её в VS Code,
в терминале ввести команду
````
git init
````
Создать файл README.md и написать в нем инструкцию

Далее сохранить изменения и добавить комментарий:
````
git commit -am "Комментарий"
````
# 3. Создать удалённый репозиторий
На GitHub нажимаем в правом углу "+" - New repository, вводим имя репозитория
# 4. Связать локальный репозиторий с удалённым
В VS Code в терминале вводим следующие команды:
````
git remote add origin https://github.com/YaroslavPolitykin/Git3.git
git branch -M main
git push -u origin main
````
Получить изменения из удалённого репозитория и выполнить слияние с локальной версией:
```bash
git pull
```
```c#
while(n<0)
{
  n++;
}
```

Отправить локальную версию репозитория на внешний `git push`
Получить список связанных репозиториев `git remote`
