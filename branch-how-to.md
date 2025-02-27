## how to create branches

1. Copy repository to your workspace
2. Create branch with "git branch Name"

## how to switch branches

Go to the this branch with "git checkout Name"

## how to push your branch

1. Add new file
2. Git status 
3. Git add "filename"
4. Git commit 
5. Git push

-----------------------------------------------------------
# Как получить ветку с сервера

1. Перейти в свой репозиторий.
2. Получить с сервера изменения во всех ветках, с помощью команды:
    ```
    git fetch
    ```

Посмотреть все ветки можно, введя в терминал:
```
git branch --all
```

# Как слиять одну ветку с другой

1. Переключитесь в ветку друга, чтобы создать её локально:
    ```
    git checkout name_of_friend_branch
    ```
2. Посмотрети все ветки и убедиться, что все сделано правильно: 
    ```
    git branch --all
    ```
3. Переключитесь в основную ветку: 
    ```
    git checkout main
    ```
4. Обьедините ветку друга с основной веткой: 
    ```
    git merge name_of_friend_branch
    ```

# Что сделать после слияния веток

1. Отправить изменения на сервер: 
    ```
    git push
    ```
2. Посмотреть историю репозиория: 
    ```
    git log
    ```