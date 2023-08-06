**Архитектура ПО (семинары)**

***HomeWork 1. Введение в понятие архитектуры, проектирование ПО и жизненный цикл программного продукта. UML-диаграммы***

Задание 1. На основе Диаграмы классов ModelElements, разработать классы: Model Store, PoligonalModel (Texture, Poligon), Flash, Camera, Scene (Реализовать диограмму на любом языке программирования)
__

Задание 2. Ознакомиться с документацией в свободном формате, которая может пригодиться Вам для дальнейшей работы:

__
ГОСТ Р ИСО/МЭК 12207-2010 Информационная технология (ИТ). Системная и программная инженерия. Процессы жизненного цикла программных средств.
ISO/IEC/IEEE 29148:2018 Systems and software engineering — Life cycle processes — Requirements engineering
Стандарты ЕСКД — единая система конструкторской документации
ГОСТ 2.001-2013 ЕСКД. Общие положения
Стандарты АСУ ГОСТ 34 — автоматизированные системы управления
Стандарты ЕСПД ГОСТ 19 — единая система программной документации


***HomeWork 2. Объектно-ориентированные паттерны***

Задание:

Прислать простую реализацию 5-ти Патернов ,на любом языке (С комментариями ), из списка -

Строитель (Builder)

Цепочка обязанностей (Chain of Responsibility)

Команда (Command)

Итератор (Iterator)

Посредник (Mediator)

Памятка (Memento)

Состояние (State)

Стратегия (Strategy)

Шаблонный метод (Template Method)

Посетитель (Visitor)

Познакомиться с другими типами паттернов(по желанию)


***HomeWork 3. Принципы SOLID***

Продолжить работу с семинара.
Hассмотрим четвертый принцип SOLID - Принцип сегрегации интерфейса (Interface Segregation Principle, ISP). Он гласит: "Клиенты не должны зависеть от интерфейсов, которые они не используют".
Вам надо написать код который исправяет эту ошибку и реализует этот принцип
Пример кода, который нарушает ISP:


И аналогично 5-ый принцип

Принцип инверсии зависимостей (Dependency Inversion Principle, DIP) гласит: "Зависимости на абстракциях. Нет зависимостей на что-то конкретное". Это означает, что высокоуровневые модули, которые обеспечивают сложную логику, должны быть независимы от низкоуровневых модулей, которые обеспечивают утилитарные функции. Оба типа модулей должны зависеть от абстракций.

Пример кода, который нарушает DIP:


***HomeWork 3. Компоненты. Принципы связности и сочетаемости компонентов***
Вам необходимо доработать код, добавив контракты к методам, документацию и обеспечив высокую связанность и низкую сочетаемость:
Файл Задание.txt


***HomeWork 5. Горизонтальные уровни и вертикальные срезы архитектуры***

Джава - https://github.com/vyntyk/Srezy.git

Питон - https://github.com/JuliaRyzhova/Software_architecture/tree/main/Seminar_5

Реализовать любой паттерн с лекции . Выпустить диаграмму компонент UML по нему.