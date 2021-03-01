# IS_RailwayStation
Информационная система «Железнодорожный вокзал»

# Общие требования
1. Данные хранить в двоичных файлах. При обработке использовать
динамические списки. Ввод и вывод данных осуществлять только через
пользовательский интерфейс разрабатываемой системы.
2. Предусмотреть контроль правильности введенных данных. Например,
при вводе даты, необходимо проконтролировать, что день – это целое число
большее нуля и меньшее 29, 30, и т.д.
3. Предусмотреть поиск и сортировку данных по некоторым
параметрам.
4. Предусмотреть интуитивно понятный интерфейс, использующий
меню (графическое или текстовое) и разделение прав различных групп
пользователей. Например, для задания 1-го варианта при заполнении данных
о работнике должен предлагаться для выбора список подразделений
предприятия, который был добавлен администратором и т.д.
5. Для организации меню использовать указатели на функции.

# Задача
Информация: рейсы – номер поезда, дата, время отправления, пункт
отправления, пункт назначения, список вагонов, для каждого вагона; вагоны –
тип, число мест, количество свободных мест, стоимость билета. Операции –
продажа билетов на определенный рейс, сдача билетов в кассу на 
определенный рейс, справки. Предусмотреть следующие группы
пользователей: администратор, кассир, пассажир.