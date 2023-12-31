**1) Почему использование тестовых заглушек может быть полезным при написании модульных тестов?**

Заглушки позволяют изолировать тестируемый класс от зависимостей, чтобы тестировать только его. Вместо объектов, которые он принимает, мы можем «подсовывать» свои объекты с элементарным поведением.

**2) Какой тип тестовой заглушки следует использовать, если вам нужно проверить, что метод был вызван с определенными аргументами?**

Фейк-заглушку. В классе, с помощью которого заглушка имитирует реальный класс, мы можем устроить сбор и хранение передаваемых в методы этого класса аргументов.

**3) Какой тип тестовой заглушки следует использовать, если вам просто нужно вернуть определенное значение или исключение в ответ на вызов метода?**

Дамми-заглушку. Но если нужна элементарная логика возврата значения в зависимости от передаваемых в метод аргументов, то её можно реализовать в стаб-заглушке.

**4) Какой тип тестовой заглушки вы бы использовали для имитации взаимодействия с внешним API или базой данных?** 

Мок-заглушку, т.к. она подменяет реальный компонент, в котором как раз можно сэмитировать работу с «внешней средой».

