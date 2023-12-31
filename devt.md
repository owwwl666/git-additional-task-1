# Задание:
Изучение команд Git Checkout/Switch, принципов Git Flow и версионирования**

Что нужно!
1. **Изучение команд checkout и switch**
Используя онлайн ресурсы и документацию Git,
изучить что делают команды `git checkout` и `git switch`, и в чем разница между ними.

2. **Создание репозитория и клонирование**
Создайть новый публичный репозиторий на GitHub.
Клонировать его на свой компьютер по ssh протоколу `git clone <url репозитория>`.

3. **Создание веток и использование checkout и switch**
Создать две ветки `feature1` и `feature2` из ветки `main` используя команды
`git switch -c feature1` и `git checkout -b feature2`.
Переключайтесь между этими ветками используя обе команды
чтобы понять разницу в их использовании.

4. **Создание файлов и коммиты**
В каждой из веток `feature1` и `feature2`, создайть файлы
`test1.txt` и `test2.txt` соответственно.
Запишите в них любой текст и выполните коммиты с соответствующими сообщениями.
ПРОЧИТАТЬ ПРО ТО КАК ПИШУТСЯ КОММИТЫ!
https://www.conventionalcommits.org/en/v1.0.0/

5. **Внесение изменений и использование тегов**
В ветке `feature1` добавьте новую строку в файл `test1.txt`, выполнить коммит
и пометить его тегом `v1.1`. Аналогично добавить новую строку в файл `test2.txt`
в ветке `feature2`, и выполнить коммит и пометьте его тегом `v1.2`.

6. **Изучение Git Flow**
Изучить принципы Git Flow, используя доступные онлайн-ресурсы.
Попытаться применить эти принципы в репозитории:
объединить изменения из веток `feature1` и `feature2` в ветку `main`
и пометить этот коммит тегом `v2.0`.

7. **Изучение версионирования**
Используя онлайн-ресурсы, изучите принципы версионирования (semantic versioning).
Поппытаться отразить эти принципы в тегах, которые вы использовали для пометки
коммитов.

8. **Публикация на GitHub**
Отправить все изменения и теги на GitHub с помощью команд
`git push origin --all` и `git push origin --tags`.

9. **Насладиться результатом!)**
Результат должен быть репозиторием на GitHub с тремя ветками
(`main`, `feature1` и `feature2`), файлами `test1.txt` и `test2.txt`,
и тремя тегами (v1.1, v1.2 и v2.0).

УДАЧИ!)
