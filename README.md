# Практическая работа #2 по Java
Здесь код для для задания.

`org/app/Main` - точка входа в приложение, там что-то вроде di

`org/cli` - два класса для вывода и ввода данных из командной строки

`org/filework` - тут все конкрентно для практики.

`org/filework/reader` - интерфейс и реализация читателя данных

`org/filework/writer` - интерфейс и реализация записывателя результата

`org/filework/counting` - класс, в котором находится логика подсчета символов

`org/filework/CountingService` - серввис, который совершает работу с помощью компонентов сверху

Все возможные ошибки обрабатываются и конретизируются, то есть в сервисе не будет ошибки `IOException`, 
а будет уже какое-то пользовательсоке исключение.



# Как использовать?
При запуске нужно будет ввести путь для двух файлов. Первый файл - для подсчета количества символов,
второй для вывода результата. Это выглдяит примерно так на Linux:
    
    Input path to file:
    /home/dan/text
    Input file for output:
    /home/dan/test
    result successfully written!


# Запуск
Для запуска можно использовать любой способ, зависимостей никаких нет, поэтому все ок.
Точка входа находится в `org/app/Main`

