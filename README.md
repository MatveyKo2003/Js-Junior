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
Пакетный менеджер-набор программного обеспечения, позволяющего управлять процессом установки, удаления, настройки и обновления различных компонентов программного обеспечения
пакетные менеджеры для:
Node. js.:npm (Node.js Package Manager) — менеджер пакетов, входящий в состав Node.js.
Windows: [chocolatey](https://chocolatey.org/) — система управления пакетами, созданная Microsoft для использования в операционной системе Windows 10 
Linux:[Dpkg] (https://www.tecmint.com/linux-package-managers/) - это базовая система управления пакетами для семейства Debian Linux
MacOS: Homebrew — система управления пакетами в macOS
- [ x] Расскажи про историю систем контроля версий (СКВ), какие были до git? Какие сейчас есть аналоги git? В чем отличительная особенность git от предыдущих СКВ?
1.[СКВ](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9E-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B5-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%BE%D0%BB%D1%8F-%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D0%B9)Система контроля версий — это система, записывающая изменения в файл или набор файлов в течение времени и позволяющая вернуться позже к определённой версии. 
2.[СКВ до git](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9A%D1%80%D0%B0%D1%82%D0%BA%D0%B0%D1%8F-%D0%B8%D1%81%D1%82%D0%BE%D1%80%D0%B8%D1%8F-Git):В 2002 году проект ядра Linux начал использовать проприетарную децентрализованную СКВ BitKeeper;
Одной из популярных СКВ была система RCS
3.[аналоги git]Subversion и Perforce, Bazaar
4.[Отличительная особенность ]Git наделили  несказанной мощью. Так как вся история проекта хранится прямо на вашем локальном диске, большинство операций кажутся чуть ли не мгновенными.
Git может найти файл месячной давности и локально вычислить изменения, вместо того, чтобы запрашивать удалённый сервер выполнить эту операцию, либо вместо получения старой версии файла с сервера и выполнения операции локально.
 Если вы в самолёте или в поезде и хотите немного поработать, вы сможете создавать коммиты без каких-либо проблем, когда будет возможность подключиться к сети, все изменения можно будет синхронизировать. Если вы ушли домой и не можете подключиться через VPN, вы всё равно сможете работать.
- [x] Перечисли стадии производственного процесса и опиши в чем их особенность
 Git-директория (Git directory), рабочая директория (working directory) и область подготовленных файлов (staging area).
 Git-директория — это то место, где Git хранит метаданные и базу объектов вашего проекта. Это самая важная часть Git, и это та часть, которая копируется при клонировании репозитория с другого компьютера.

Рабочая директория является снимком версии проекта. Файлы распаковываются из сжатой базы данных в Git-директории и располагаются на диске, для того чтобы их можно было изменять и использовать.

Область подготовленных файлов — это файл, обычно располагающийся в вашей Git-директории, в нём содержится информация о том, какие изменения попадут в следующий коммит. Эту область ещё называют “индекс”, однако называть её stage-область также общепринято.
- [ ] Что такое репозиторий? Какие виды репозиториев бывают? Как создать репозиторий? Как называется процесс создания репозитория? Какой файл создается в результате создания репозитория? Что такое директория и назови синоним? Что такое файл? Как проверить что в директории есть репозиторий?
- [ ] Перечисли основные команды git и что они делают?
- [ ] Какие данные имеет коммит?
- [ ] Какие 2 состояния имеет файл в репозитории в рабочей копии? Одно из этих состояний делится на три - какие? Какие команды использовать для перехода между состояниями, назови все.
- [ ] Как работает git изнутри?
- [ ] Что такое ветка? Какая ветка создается автоматически при иницализации? Для чего используется ветвление в рабочем процессе? Как определить какая ветка активная (приведи спецсимвол и кодовое обозначение)? Какие 2 основные операции по объединению веток, в чем их отличия?
- [ ] Перечисли команды взаимодействия с удаленным репозиторием?
- [ ] Для чего нужен GitHub? 
