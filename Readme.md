# Инструкция по работе с Git и удалёнными репозиториями

## Создание репозитория
Для того, чтобы добавить версионность к созданной папке, и создать в ней локальный репозиторий, для этого необходимо открыть окно терминала в этой папке и написать команду *git init*. Тогда Ваша папка станет репозиторием, и в ней появится скрытая папка .git

## Добавление файлов в репозиторий
Добавить версионность к файлу, находящемуся в папке-репозитории, можно с помощью команды *git add*. Пишется она следующим образом *git add <название файла>*

## Создание коммитов
Для того, чтобы зафиксировать изменения в текущей версии используется команда *git commit*. Используется она следующим образом: *git commit -m "<Сообщение к коммиту>"*. Сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**

## Просмотр истории коммитов
Для просмотра истории всех сделанных коммитов используется команда *git log*. Чтобы увидеть всю историю коммитов, в папке репозитория в терминале необходимо написать *git log*

## Переключение между коммитами
Для того, чтобы переключаться между коммитами, необходимо использовать команду *git checkout*. Используется она следующим образом: *git checkout <номер коммита>*. Номер коммита можно взять, просмотрев список всех коммитов. 

## Создание ветки
Для того, чтобы создать новую ветку используется команда *git branch*. В папке с репозиторием напишите команду *git branch <название ветки*. Проверить то, что ветка создалась можно с помощью команды *git branch* в папке с репозиторием.

## Переключение между вектками
Для того, чтобы переключиться между ветками используется команда *git checkout*. Применяется она следующим образом: в папке с репозиторием необходимо написать *git checkout <название созданной ветки>*

## Слияние веток
Слияние веток можно произвести, использовав команду *git merge*. Используется она следующим образом: в папке с репозиторием надо написать команду *git merge <сливаемая ветка*>, сделать это необходимо в ветке, куда происходит слияния. При слиянии веток возможны **КОНФЛИКТЫ**. В случае возникновения конфликта, необходимо вручную получить желаемую версию файла, после чего сделать коммит(см. инструкцию выше)

## Удаление веток
