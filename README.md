# LR6
Лабораторная работа №6
1. Форкаем репозиторий на свой профиль</br>
2. Задаем имя пользователя и email </br>
![image](images/1.jpg)</br>
3. Клонируем удаленный репозиторий на компьютер</br>
![image](images/2.jpg)
4. Добавляем файл через интерфейс Github
![image](images/3.jpg)
![image](images/4.jpg)
5. Подтягиваем изменения в локальный репозиторий
![image](images/5.jpg)
6. Получаем историю для каждой ветки
![image](images/6.jpg)
7. Смотрим последние изменения ветки (изменений много, но в качестве примера представил один скриншот)
![image](images/7.jpg)
8. Выполняется слияние и разрешается конфиликт </br>
8.1. Переходим в ветку brunch1 </br>
![image](images/8.jpg)</br>
8.2. Выполняем слияние и получаем сообщение о конфликте</br>
![image](images/9.jpg)</br>
8.3. Выясняем причину конфликта </br>
![image](images/10.jpg)</br>
8.4. Исправляем причину конфикта </br>
![image](images/11.jpg) </br>
8.5. Добавляем содержимое рабочего каталога в индекс для последующего коммита </br>
![image](images/12.jpg) </br>
8.6. Смотрим, исправлена ли ошибка и завершаем merge </br>
![image](images/13.jpg)
9. Удаляем побочную ветку master </br>
![image](images/14.jpg)
10. Создаю новый файл и коммичу его, оставляя комментарий </br>
![image](images/15.jpg) </br>
11. Добавляю строчку в файл </br>
![image](images/16.jpg) </br>
12. Удаляю строчку из файла
![image](images/17.jpg)
13. Делаю хард откат коммита </br>
![image](images/18.jpg)
14. Создаю ветку для отчета и перехожу на неё </br>
![image](images/19.jpg)
15. Отправляю все данные на удаленный репозиторий 
![image](image/20.jpg)
# Лог команд
git config global user.name/email </br>
git clone https://github.com/svifec/LR6 </br>
cd LR6 </br>
git pull </br>
git reflog --all </br>
git log -p -2 </br>
git checkout branch1 </br>
git merge master </br>
git diff </br>
git add mergefile.txt </br>
git status </br>
git commit -m "Merged" </br>
git branch -d master </br>
git status </br>
git add file2.txt </br>
git commit -m "Создала новый файл" </br>
git status </br>
git add file2.txt </br>
git commit -m "Заполнила file2" </br>
git status </br>
git add file2.txt </br>
git status </br>
git commit -m "Удалила file2" </br>
git reset --hard HEAD </br>
git checkout -b otchet </br>
git push --set-upstream origin otchet </br>
# История операций
fc55fc1 2024-11-13 | 4316KramarenkoSE | Удалила file2 </br>
1cd51c2 2024-11-13 | 4316KramarenkoSE | Заполнила file2 </br>
4414e7b 2024-11-13 | 4316KramarenkoSE | Создала новый файл </br>
484b05d 2024-11-13 | 4316KramarenkoSE | Merged </br>
124ed9f 2024-11-13 | svifec | Create New File </br>
921f53b 2020-11-21 | Kurtyanik | Обновление информации </br>
0f9f50d 2020-11-21 | Kurtyanik | Заполнил файл </br>
c08a654 2020-11-21 | Kurtyanik | Файл создан пустым </br>
3c6e913 2020-11-21 | Kurtyanik | Initial commit </br>

