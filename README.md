![](https://blog.alexdevero.com/wp-content/uploads/2020/02/10-02-20-javascript-objects-friendly-introduction-p1-blog.jpg)
# tabele of contents
+ 01 Object
+ 02 Destructing
+ 03 Spread
+ this
# Что такое object в javascript ?
+ **это набор свойств. Каждое свойство состоит из названия и значения. Название может быть строкой или символом, а значение может быть любым. Объекты в JavaScript используются повсюду, особенно для хранения данных**
![](https://www.scientecheasy.com/wp-content/uploads/2022/03/javascript-object-example.png)
### ```java
### const car = {
  ### type: "Fiat",
  ### model: "500",
  ### color: "white"
### };
# Методы
## Методы — это функции, которые являются свойствами объекта:
### const person = {
  ### firstName: "John",
  ### lastName: "Doe",
  ### age: 30,
  ### eyeColor: "blue",
  ### fullName: function() {
  ### return this.firstName + " " + this.lastName;
 ### }
### };
# Object keys
+ ## Статический Object.keys()метод возвращает массив собственных перечислимых имен свойств заданного объекта, имеющих строковый ключ.
### const object1 = {
 ### a: 'somestring',
 ### b: 42,
 ### c: false,
### };
### console.log(Object.keys(object1));
### // Expected output: Array ["a", "b", "c"]
# Доступ к свойствам объекта
+ # Вы можете получить доступ к свойствам объекта, используя точечную нотацию или квадратные скобки:
### console.log(person.name); // Точечная нотация
### console.log(person["age"]); // Квадратные скобки
![](https://marketplace.canva.com/EAFGH7TQKS8/3/0/1600w/canva-thank-you-card-uMCuw9XtkYc.jpg)
