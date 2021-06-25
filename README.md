# Test_repo
yum install git <br>
apt install git <br>

git config --global user.name "MBA" <br>
git config --global user.email "MBA@gmail.com" <br>
git config -l <br>

git init . - Создание Git-репозитория <br>
git add * или git add .   - Запись изменений в репозиторий, добавление файлов в репозиторий (можно указать ) <br>
git status - Посмотреть статус git <br>
git commit -m "My initial version" - Запись изменений в репозиторий - Git, опязательно указываем комментарий после ключа -m <br>

git log - проверить статус всех commit <br>
git log -1 - посмотреть последний commit (цифра 1)<br>
git log -1 -p - посмотреть какие изменения были сделаны в последнем commit<br>

git diff --staged - показывает разницу между staged и последним commit<br>
git restore file1.txt - отменить последние изменения в файле file1.txt<br>


nano .gitignore - создать файл в котором описаны файлы и директории, которые будут игнорироваться Git'ом. В файле просто пишем имена файлов и директорий например:<br>
# cat .gitignore<br>
*.log<br>
logs/<br>
file1.txt<br>
