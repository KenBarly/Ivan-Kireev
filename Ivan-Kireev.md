# Git -  самая популярная система контроля версий!
**Git — это распределенная система управления версиями, то есть локальный клон проекта — это полный репозиторий управления версиями. Полнофункциональные локальные репозитории упрощают работу как в автономном, так и в удаленном режиме. Разработчики фиксируют свою работу локально, а затем синхронизируют свою копию репозитория с копией на сервере. Эта парадигма отличается от централизованных систем управления версиями, где клиенты должны синхронизировать код с сервером перед созданием новой версии кода.**

## Перечень команд Git:

1. *git --version* - проверка текущей версии программы.

2. *git init* - инициализация папки, в которой находится текущий проект.

3. *git status* - отображение текущего состояния программы (есть ли изменения, которые нужно закоммитить (сохранить)).

4. *git add . (git add <filename.exstension>)* - добавление файла.

5. *git commit* - фиксация (сохранение) сделанных в файле изменений.

6. *git log* - вывод журнала изменений.

7. *git checkout* - переключение между версиями (коммитами) файла.

8. *git diff* - отображение разницы между текущим файлом и сохраненными.

9. *git branch* - вывод на экран текущей ветки или создание новой ветки командой git branch + название новой ветки.

10. *git merge* - команда для слияния любой ветки с текущей веткой (с которой работаем в данный момент). Чтобы слить любую ветку с текущей, вызываем
**git merge <имя ветки для слияния с текущей>**.

11. *git branch -d* - команда для удаления ветки, использование которой больше не требуется. Чтобы удалить ветку вызываем **git branch -d <имя ветки, которую требуется удалить>**.

12. *git log --graph* - команда, позволяющая отобразить коммиты в виде дерева.

13. *git ignore* - команда, исключающая ненужные файлы из загрузки. Например, файлы изображений. ![git](git.png)

# Конфликт изменений

**При работе в двух ветках одновременно может
возникнуть ситуация, когда в одной и другой
ветке мы по-разному изменили блок текста.
Если затем мы попробуем слить эти ветки, Git
сообщит о конфликте и предложит выбрать,
какие же изменения записать.**

**Поэтому у проекта в репозитории должен быть один
ответственный пользователь, наделённый правом проводить
слияния и разрешать конфликты.**

# Работа с удаленными репозиториями

**GitHub** — это сервис компании Microsoft, который позволяет интегрироваться с
программой Git и настроить удалённую работу с вашим репозиторием.

*git clone* - команда, позволяющая скопировать (клонировать) удаленный (внешний) репозиторий себе на ПК.

*cd* (change directory) — поменять директорию. После указанной команды указывается имя директории.

*git pull* - команда, позволяющая скачать содержимое текущего репозитория и автоматически сделать *merge* с нашей версией.

*git push* - команда, позволяющая отправить нашу версию репозитория на внешний (удаленный) репозиторий.

*pull request* — предложение изменения кода в чужом репозитории.

Алгоритм **pull request**:

* делаем **fork** "чужого" репозитория;
* делаем **clone** "своей" версии репозитория;
* создаем **новую** ветку и в **НЕЕ** вносим свои изменения;
* фиксируем изменения (делаем **коммиты**);
* отправляем (**push**) свою версию в **свой** GitHub;
* на сайте GitHub нажимаем кнопку **pull request**.

## Историческая справка

*Первый частный репозиторий был создан 12 января 2008. К концу 2011 года в проекте уже было зарегистрировано более миллиона пользователей и более двух миллионов репозиториев. По состоянию на март 2017 года на сайте существовало более 58 миллионов репозиториев. В конце 2008 года GitHub получил награду как «Лучший стартап-дебют». На Github располагается копия исходного кода ядра Linux. Многие крупные IT-компании размещают свои официальные репозитории на этом сервисе.*

### Более подробную информацию по работе с Git ![Гремлин](Gremlin.jpg) 

Вы можете получить на [лекциях](https://gb.ru/lessons/261653/ "Первая лекция GB") и [семинарах](https://gb.ru/lessons/265426/ "Первый семинар GB") GeekBrains.