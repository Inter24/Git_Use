  [к содержанию](./readme.md)
  ---
# Заливка данных на GIT
Проверка состояния:
```
git status
```
Авторизация:
```
git config --global user.name "My Name"
git config --global user.email myEmail@example.com
```

Собираем данные и отправляем:
```
git init
git add .
git commit -m "COMMIT NAME"
git remote add origin https://github.com/Inter24/Git_Use.git
git push
```

Создание новой ветки
```
git push --set-upstream origin master
```