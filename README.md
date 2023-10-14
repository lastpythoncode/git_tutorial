# git_tutorial
![Image alt](https://github.com/lastpythoncode/git_tutorial/blob/main/img_1.jpg)


Привет дорогой друг , это небольшой мануал по работе с git под виндой.
Цель данного мануала создание удобной шпорки , в которую я буду заглядывать при необходимости. 
В данном мануале не будет написано о том что это и для чего это, так как подразумевается что основная аудитория уже имеет 
определённые познания в области IT. В своём мануале я не буду приводить исчерпывающую информацию о данной технологии, скорее приведу минимум команд необходимых для работы с git и в дальшейшем буду прописывать дополнительные команды по мере развития...

ссылка на git: https://git-scm.com/download/win

### настройка git

(прописываем свой юзер_нейм и емеил)<br>
git config --global user.name '<ваше_имя>'<br>
git config --global user.email '<адрес_почты@email.com>'<br>

### команды для работы
инициализируем репозиторий(прописываем в папке с проектом)<br>
```
git init
```

чекаем изменения<br>
```
git status
```

добавляем все файлы в будующий коммит<br>
```
git add .
```

создаём коммит (обязательно с вразумительным комментарием)<br>
```
git commit -m '<комментарий>'
```

запушиваем коммит на гитхаб<br>
```
git push
```
