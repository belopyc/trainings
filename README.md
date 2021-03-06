# Java Core Trainings

[![Build Status](https://travis-ci.org/jelem/homework.svg?branch=master)](https://travis-ci.org/parkhomenko/trainings)

1. Сделайте копию текущего репозитория в своём аккаунте github. Для этого вам нужно нажать кнопку **Fork** в правом верхнем углу, остальное всё сделает для вас github
2. Склонируйте свою копию репозитория (которая должна была появиться после выполнения первого шага) из github к себе на локальный компьютер (измените **mygitaccount** на свой):
```bash
git clone https://github.com/mygitaccount/trainings.git
```
3. В папке task``_``{текущее задание} создайте папку со своими именем и фамилией в формате: **john.doe**
4. Создайте gradle проект в этой папке (можно использовать IDE)
5. Выполните задания, которые описаны в файле **README.md** внутри соответствующей папки task``_``{текущее задание}
6. Выполните проверку стилей и наличие ошибок (checkstyle и findbugs). Для этого вам нужно будет выполнить команду из корня репозитория (если в отчетах, которые сформирует эта команда есть ошибки, исправьте их):
```bash
gradle check
```
7. Занесите ваши изменения в свой аккаунт в гитхабе:
```bash
git add .
git commit -m "какое-то сообщение"
git push origin master
```
8. Должна запуститься автоматическая проверка ошибок с помощью https://travis-ci.org/mygitaccount/trainings. Если всё прошло успешно, переходите к следующему пункту
9. Выполните pull request, для этого перейдите в свой репозиторий в гитхабе (trainings в своём аккаунте) и нажмите кнопку **New Pull Request**
10. Если в ходе кодривью вы получили **reject**, исправьте замечания и сделайте еще один коммит и пуш в свой репозиторий (шаг 7)
11. Для получения новых заданий (получения новых изменений из главного репозитория) нужно сделать шаги:
```bash
git remote add upstream https://github.com/parkhomenko/trainings.git #эту команду только один раз
git pull upstream master #загружает новые изменения из главного репозитория
```
