# Инструкция по работе с Git

## Что такое Git?
***Git*** - самая популярная реализация распределенной системы контроля версий(версионность поддерживания и на сервере, и у каждого клиента). Самой распространненной реализацией ***Git*** является (GitHub)[http://github.com]

## Подготовка репозитория

Для создания репозитория используется команда *git init*. Для этого необхобимо открыть в терминале папку с будущем репозиторием и написать *git init*

## Добавление файлов к коммиту

Для добавления файла к новому коммиту используется команда *git add*. Используется она следующим образом: в терминале с папкой-репозиторием пишет *git add <название файла>*.

## Создание коммита

Для создания новой фиксации(коммита) используется команда *git commit*. Для этого в терминале с папкой-репозиторием пишется *git commit -m "<сообщение к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!***

## Перемещение между комитами

Для перемещения на другую фиксацию(коммит) используется команда *git checkout*. Для этого необходимоБ как показано в прошлом пунктеБ в журнале изменеий найти необходимый коммит и его хеш(номер)Б после чего в терминале с папкой-репозиторием надо написать *git checkout <хеш коммита>*. После выполнения этой команды мы попадаем в состояние **detached head**, в котором никакие следующие коммиты сохранять не будут. Для выхода из этого состояния необходимо написать *git checkout master*.

## Ветки в git

Чтобы в Git добавить ветку мы используем команду *"git branch <name of new branch>"*

## Журнал изменений

Для просмотра истории изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием необходимо написать *git log*.

## Слияние веток и разрешение кофликтов

## Удаление веток