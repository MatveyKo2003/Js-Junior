# Js-Junior

Задачи:
========
0. Установи пакетный менеджер для винды: [о пакетном менеджере](https://ru.wikipedia.org/wiki/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0_%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_%D0%BF%D0%B0%D0%BA%D0%B5%D1%82%D0%B0%D0%BC%D0%B8), а здесь сама [ссылка с описанием установки](https://chocolatey.org/install). Тебе нужно запустить [интерпретатор командной строки](https://ru.wikipedia.org/wiki/Cmd.exe) - способ запусков много, как, пример, [здесь](https://superuser.com/questions/968214/open-cmd-as-admin-with-windowsr-shortcut)
0.1 Установи teamviewer [ссылка](https://chocolatey.org/packages/teamviewer)
1. Прочитать про редактор кода бегло общую информацию [здесь](https://ru.wikipedia.org/wiki/%D0%A0%D0%B5%D0%B4%D0%B0%D0%BA%D1%82%D0%BE%D1%80_%D0%B8%D1%81%D1%85%D0%BE%D0%B4%D0%BD%D0%BE%D0%B3%D0%BE_%D0%BA%D0%BE%D0%B4%D0%B0)
2. Установить [VSCode](https://chocolatey.org/packages/vscode) - прочитай до конца, там описывают параметры установки, Твоя задача - установить без добавления иконки на рабочий стол
3. Установить Распределенную систему контроля версий - [git](https://chocolatey.org/packages/git) его [документация-обучалка](https://git-scm.com/book/ru/v2)
- Обязательно для прочтения [ссылка](https://ru.hexlet.io/blog/posts/environment) и это [ссылка](https://ru.wikipedia.org/wiki/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0_%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F%D0%BC%D0%B8)
- Настроить git - [ссылка](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-Git) (*Выбор редактора* - этот раздел пропусти)
- Команды git'а [ссылка](https://services.github.com/on-demand/downloads/github-git-cheat-sheet/)
4. Пройти весь [курс по git](https://ru.hexlet.io/courses/intro_to_git) (нужно зарегаться, потом по ссылке перейти и нажать на кнопку *Вступить в курс и начать*)
6. Пройти курс до конца [ссылка](https://githowto.com/ru/create_a_project)


Вопросы для самоконтроля:
===========================
- [x] Что такое пакетный менеджер? Назови пакетные менеджеры для Node.js, Windows, Linux, MacOS?

1.Пакетный менеджер-набор программного обеспечения, позволяющего управлять процессом установки, удаления, настройки и обновления различных компонентов программного обеспечения
пакетные менеджеры для:

Node. js.:npm (Node.js Package Manager) — менеджер пакетов, входящий в состав Node.js.

Windows: [chocolatey](https://chocolatey.org/) — система управления пакетами, созданная Microsoft для использования в операционной системе Windows 10 

Linux:[Dpkg](https://www.tecmint.com/linux-package-managers/) - это базовая система управления пакетами для семейства Debian Linux

MacOS: Homebrew — система управления пакетами в macOS

-----------------------------------------------------------------------

- [ ] Что такое локальный компьютер? Что такое сервер? В чем их отличия?

-----------------------------------------------------------------------

- [ ] Расскажи про историю систем контроля версий (СКВ), какие были до git (их характеристика, а не названия)? Какие сейчас (2018г) есть аналоги git? В чем отличительная особенность git от предыдущих СКВ?

Пример: я создам файл ava.js со строкой **console.log('Hello Zakhar')** и с течением времени внесу в строку изменения **console.log('Hello Matvei')**. 

\\\\\\
Ситуация 1: У меня нет СКВ. Как мне показать что файл был изменен? Смогу ли я после того как изменю файл и сохраню его, узнать, что было в строке до того, как я туда вписал **console.log('Hello Matvei')**? Почему?

\\\\\\
Ситуация 2: У меня СКВ первого поколения и я работаю с другом над этим файлом. 

Смогу ли я узнать, что было в строке до того, как я туда вписал **console.log('Hello Matvei')**? 

Как сделать так, чтобы мой друг у которого есть файл со строкой **console.log('Hello Zakhar')** на его локальном компьютере получил копию моего файла со строкой **console.log('Hello Matvei')**? 

ПЛЮС: Вдруг друг решил сам добавить строку в старый файл в результате у него такой код:
```js
console.log('Hello Zakhar')
console.log('Hello Ivan')
```

Опиши процесс объединения наших с иваном файлов (для меня и для Ивана), чтобы в итоге мой файл и файл Ивана выглядел так:
```js
console.log('Hello Matvei')
console.log('Hello Ivan')
```

\\\\\\
Ситуация 3: У меня СКВ второго поколения и я работаю с другом над одним файлом. 

Прежде вопрос: Где находится этот файл?

В это время я в лесу без интернета. В это время Иван решил изменить файл на сервере с таким содержанием:
```js
console.log('Hello Chakhar')
console.log('Hello Ivan')
```
Когда я узнаю об этом изменении? 

Как мне внести измения в этот файл? Где я смогу внести изменения в этот файл?

Как скоро Иван узнает о том, что я внес изменения?

\\\\\\
Ситуация 4: У меня СКВ второго поколения и я работаю с другом над одним файлом.

вопросы те же

Прежде вопрос: Где находится этот файл?

В это время я в лесу без интернета. В это время Иван решил изменить файл и добавить его на сервер с таким содержанием:
```js
console.log('Hello Chakhar')
console.log('Hello Ivan')
```
Когда я узнаю об этом изменении? 

Как мне внести измения в этот файл? Где я смогу внести изменения в этот файл? Как скоро Иван узнает о том, что я внес изменения?



1.[СКВ](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9E-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B5-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%BE%D0%BB%D1%8F-%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D0%B9)Система контроля версий — это система, записывающая изменения в файл или набор файлов в течение времени и позволяющая вернуться позже к определённой версии.

-----------------------------------------------------------------------

- [ ] Перечисли стадии рабочего процесса в СКВ и опиши в чем их особенность
q
-----------------------------------------------------------------------

- [x] Перечисли основные команды git и что они делают?

1.git add
Команда git add добавляет содержимое рабочей директории в индекс (staging area) для последующего коммита.

2.git status
Команда git status показывает состояния файлов в рабочей директории и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе. Вдобавок к этому выводятся подсказки о том, как изменить состояние файлов.

3.git diff
Команда git diff используется для вычисления разницы между любыми двумя Git деревьями. 

4.git difftool
Команда git difftool просто запускает внешнюю утилиту сравнения для показа различий в двух деревьях, на случай если вы хотите использовать что-либо отличное от встроенного просмотрщика git diff.

5.git commit
Команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.

6.git reset
Команда git reset, как можно догадаться из названия, используется в основном для отмены изменений. Она изменяет указатель HEAD и, опционально, состояние индекса.

7.git rm
Команда git rm используется в Git для удаления файлов из индекса и рабочей директории. Она похожа на git add с тем лишь исключением, что она удаляет, а не добавляет файлы для следующего коммита.

8.git mv
Команда git mv — это всего лишь удобный способ переместить файл, а затем выполнить git add для нового файла и git rm для старого.

9.git clean
Команда git clean используется для удаления мусора из рабочей директории. Это могут быть результаты сборки проекта или файлы конфликтов слияний.

-----------------------------------------------------------------------

- [ ] Какие данные имеет коммит?

Именование. Коммиты должны иметь осмысленное описание. Например: "fix scrolling".

-----------------------------------------------------------------------

- [x] Какие 2 состояния имеет файл в репозитории в рабочей копии? 

1.Каждый файл в вашем рабочем каталоге может находиться в одном из двух состояний: 
под версионным контролем (отслеживаемые) и нет (неотслеживаемые). 

Отслеживаемые файлы — это те файлы, которые были в последнем слепке состояния проекта (snapshot); они могут быть неизменёнными, изменёнными или подготовленными к коммиту (staged). 

Неотслеживаемые файлы — это всё остальное, любые файлы в вашем рабочем каталоге, которые не входили в ваш последний слепок состояния и не подготовлены к коммиту. 

Когда вы впервые клонируете репозиторий, все файлы будут отслеживаемыми и неизменёнными, потому что вы только взяли их из хранилища (checked them out) и ничего пока не редактировали.

-----------------------------------------------------------------------

- [ ] Одно из этих состояний делится на три - какие? 

-----------------------------------------------------------------------

- [ ] Какие команды использовать для перехода между состояниями, назови все (назвал не все).

2.Перейти к последнему состоянию в ветке master:
git checkout master

Перейти к определённому состоянию в текущей ветке:
git checkout <hash>

-----------------------------------------------------------------------

- [ ] Как работает git изнутри?

-----------------------------------------------------------------------

- [ ] Что такое ветка? Какая ветка создается автоматически при иницализации? Для чего используется ветвление в рабочем процессе? Как определить какая ветка активная (приведи спецсимвол и кодовое обозначение)? Какие 2 основные операции по объединению веток, в чем их отличия?

-----------------------------------------------------------------------

- [ ] Перечисли команды взаимодействия с удаленным репозиторием? (**названы не все**)
 
 Для того, чтобы просмотреть список настроенных удалённых репозиториев, вы можете запустить команду git remote. Она выведет названия доступных удалённых репозиториев
 
 Для того, чтобы добавить удалённый репозиторий и присвоить ему имя (shortname), просто выполните команду git remote add [shortname] [url]
 
 если вы хотите получить изменения, которые есть у Пола, но нету у вас, вы можете выполнить команду git fetch pb
 Отправка изменений в удаленный репозиторий (Push): git push [remote-name] [branch-name]
 
 Просмотр удаленного репозитория:git remote show [remote-name]
 
Удаление и переименование удалённых репозиториев
Для переименования ссылок в новых версиях Git’а можно вылолнить git remote rename

-----------------------------------------------------------------------

- [ ] Для чего нужен GitHub? (**дополни ответ**) 
 GitHub позволяет Вам совместно работать с другими людьми над одним и тем же кодом
