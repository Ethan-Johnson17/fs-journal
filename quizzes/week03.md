# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction, Encapsulation, Inheritance, Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
This is similar to when we did the zoo project. In that sitaution, we used a for key in loop. for(let key in staff){property.name
}
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
It is the wrapping up of data, code, and methods together in a class in order to hide certain data for the sake of privacy.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A Class is a blueprint, it generally doesn't contain any actual data. This instance of the class contains the data.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is an instance that serves as the "safety layer" in a sense, preventing the origina from being accessed by those not authorized
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The MVC pattern is meant to make code cleaner and keep data private
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is what users interact with
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service is what communicates the controller to the proxystate and vice versa
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is where the blueprint of the class is stored.
```
