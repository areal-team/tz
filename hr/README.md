# Тестовое задание: Учет сотрудников

## Подготовительные работы
Создать новый репозиторий на GitHub (ссылку на него будет необходимо отправить после выполнения задания)
## Комментарий
Коммититься нужно как можно чаще, при проверке будет учитываться содержательность сообщений коммита и порции, которыми коммиты осуществляются,
время по задаче будет оцениваться как время между первым (инициализированным коммитом) и последним.
## Задание
Предполагается, что HR ведёт кадровый учёт сотрудников организации. 

1. Необходимо продумать и спроектировать базу данных,
2. Вывести на экран веб-приложения таблицу с данными по сотрудникам.

Информация о сотруднике должна включать следующий набор данных:
- ФИО,
- Дата рождения,
- Серия/номер паспорта, (формат ввода по маске)
- Контактная информация, (формат ввода по маске)
- Адрес проживания,
- Отдел,
- Должность,
- Размер зарплаты,
- Дата принятия на работу

## Функциональные возможности HR-специалиста:
- Просматривать информацию по всем сотрудникам;
- Возможность фильтрации содержимого таблицы по отделу, должности;
- Создавать нового сотрудника;
- Найти конкретного сотрудника по ФИО; 
- Редактировать информацию о сотруднике;
- Уволить сотрудника
#### ВАЖНО:
Функция увольнения не удаляет сотрудника из таблицы.

Если сотрудник считается уволенным, блокируется функция редактирования информации, сотрудник получает метку «Уволен»

## Стек технологий:
**Бэкенд:** на выбор участника (PHP или JS)

**Фронтенд:** html, css
