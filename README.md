![](https://blog.alexdevero.com/wp-content/uploads/2020/02/10-02-20-javascript-objects-friendly-introduction-p1-blog.jpg)
# tabele of contents
+ 01 Object
+ 02 Destructing
+ 03 Spread
+ this
# Что такое object в javascript ?
+ **это набор свойств. Каждое свойство состоит из названия и значения. Название может быть строкой или символом, а значение может быть любым. Объекты в JavaScript используются повсюду, особенно для хранения данных**
![](https://www.scientecheasy.com/wp-content/uploads/2022/03/javascript-object-example.png)
```java
 const car = {
  type: "Fiat",
  model: "500",
  color: "white"
};
```
# Методы
**Методы — это функции, которые являются свойствами объекта:**
```
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 30,
  eyeColor: "blue",
  fullName: function() {
    return this.firstName + " " + this.lastName;
  }
};
```
