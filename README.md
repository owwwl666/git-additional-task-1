# Описание
Репозиторий создан в образовательных целях на проработку ключевых команд: `git clone` `git commit` `git checkout` `git switch`

## Реализация
- Создать репозиторий на GitHub
- Клонировать локально через [ssh](https://docs.github.com/ru/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) протокол с помощью команды `git clone <url репозитория>`
- Создать в проекте две ветки `feature1` и `feature2` из ветки `main` используя команды

  ```
  git switch -c feature1 
  ```  
  ```
  git checkout -b feature2
  ```
  Переключайтесь между этими ветками используя обе команды
  
 - В каждой из веток `feature1` и `feature2`, создайть файлы `test1.txt` и `test2.txt`, передав в них какой-либо текст с помощью команды
    
    ```
    nano text1.txt
    ```
    
    ```
    nano text2.txt
    ```
   
  - Добавить каждый файл в соответствующей ветке в индекс через `git add`
  - Закомитить `git commit -m "Название коммита"`
  - В ветке `feature1` добавьте новую строку в файл `test1.txt`, выполнить коммит и пометить его тегом `v1.1`. Аналогично добавить новую строку в файл `test2.txt`в ветке `feature2`, и выполнить коммит и пометьте его тегом `v1.2`.
    
    ```
    git tag v1.1-lw
    ```
    
    ```
    git tag v1.2-lw
    ```
  - объединить изменения из веток `feature1` и `feature2` в ветку `main` и пометить этот коммит тегом `v2.0`.
    
    ```
    git merge feature2
    ```
    
    ```
    git merge feature1
    ```
    
    ```
    git tag v2.0-lw
    ```
  - Отправить все изменения и теги на GitHub с помощью команд:
    ```
    git push origin --all
    ```
    
    ```
    git push origin --tags
    ```
