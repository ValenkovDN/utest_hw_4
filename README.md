1. Почему использование тестовых заглушек может быть полезным при написании модульных тестов?
Потому что использование тестовых заглушек упрощает тестирование: они передаются тестируемой системе вместо реальных зависимостей, настройка и сопровождение которых могут быть сопряжены с определёнными сложностями.Кроме того, это позволяет проверять код независимо от остальной системы

2. Какой тип тестовой заглушки следует использовать, если вам нужно проверить, что метод был вызван с определенными аргументами?
Для проверки работоспособности метода можно передать заглушку типа DUMMY с предопределённым значением.

3. Какой тип тестовой заглушки следует использовать, если вам просто нужно вернуть определенное значение или исключение в ответ на вызов метода?
Нужно вернуть заглушку типа MOCK

4. Какой тип тестовой заглушки вы бы использовали для имитации взаимодействия с внешним API или базой данных?
Для имитации взаимодействия с внешними системами нужно использовать заглушки типа MOCK.