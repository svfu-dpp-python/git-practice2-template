# Git: Практика 2

1. Проверьте параметры `user.name` и `user.email` в настройках системы Git и 
   измените их при необходимости.

   ```
   git config --global --list
   ```

2. Перейдите в каталог для проектов (например `Documents`), склонируйте свой
   репозиторий и перейдите в каталог репозитория:

   ```
   cd <каталог проектов>
   git clone <URL-репозитория>
   cd <каталог репозитория>
   ```

3. Проверьте имеющиеся ветки, создайте новую ветку `feature-nod-nok`,
   переключитесь в нее и проверьте имеющиеся ветки снова:

   ```
   git branch -a
   git branch feature-nod-nok
   git checkout feature-nod-nok
   git branch -a
   ```

4. Напишите код внутри функции `nod()`, определяющей наибольший общий делитель
   чисел `a` и `b`, и выполните первый коммит:

   ```
   git status
   git add <измененные файлы>
   git commit -m "<сообщение>"
   ```

5. Напишите код внутри функции `nok()`, определяющей наименьшее общее кратное
   чисел `a` и `b`, и выполните второй коммит.

   ```
   git status
   git add <измененные файлы>
   git commit -m "<сообщение>"
   ```

6. Отправьте изменения в GitHub:

   ```
   git push -u origin feature-nod-nok
   ```

6. Переключитесь на ветку `main`.

   ```
   git checkout main
   ```

7. Выполните объединение с веткой `feature-nod-nok`.

   ```
   git merge feature-nod-nok
   ```

8. Отправьте изменения в GitHub.

   ```
   git push
   ```

9. Проверьте произведенные изменения в GitHub. Найдите кнопку переключающие
   ветки. Найдите историю коммитов. Проверьте вкладку Actions.
