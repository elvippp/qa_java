# МОК тесты

### Тестовые сценарии:
1. Класс Lion не должен зависеть от класса Feline. Используй принцип инъекции зависимостей.
2. Напиши моки с помощью Mockito. Какие именно понадобятся — определи самостоятельно.
3. Напиши тесты на классы Feline, Cat и Lion.
4. Подумай, где можно применить параметризацию. Реализуй параметризованные тесты.
5. Оцени покрытие с помощью Jacoco: оно должно быть не менее 100% для классов Feline, Cat и Lion..

##### Дополнительное задание
1. Создай класс льва Алекса из мультфильма «Мадагаскар». Он будет наследником обычного льва.

*Помимо обычных методов у него есть свои*: 
- getFriends() возвращает список имён его друзей — зебры Марти, бегемотихи Глории и жирафа Мелман;
- getPlaceOfLiving() возвращает место, где он живёт — Нью-Йоркский зоопарк.

Также нужно переопределить метод *getKittens*, потому что у Алекса нет львят. 

А ещё — написать свой конструктор, так как в классе Lion нет дефолтного конструктора. Алекс самец, поэтому в конструктор класса Lion всегда будет передаваться одно и то же значение. 
