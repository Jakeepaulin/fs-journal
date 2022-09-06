# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?

<!-- enter you answer in the space below -->

```
Abstraction, Encapsulation, Inheritance, and Polymorphism.
```

**2.** How would you access the `name` of the below object using the `property` variable?

```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey",
};
let property = "name";
```

<!-- enter you answer in the space below -->

```
console.log(staff.property)
```

**3.** What is Encapsulation?

<!-- enter you answer in the space below -->

```
Encapsulation is the gathering and bundling of data and the methods that restrict access to that data from outside the bundle.
```

**4.** What does the S stand for in the `SOLID` principles?

<!-- enter you answer in the space below -->

```
Single Responsibility Principle
```

**5.** What the difference between a `class` and an instance of a `class`?

<!-- enter you answer in the space below -->

```
The difference is that a 'class' is a blueprint you use to create objects while an instance of a 'class' is an object you use to make a specific class.
```

**6.** What is a `Proxy` object?

<!-- enter you answer in the space below -->

```
A proxy object is an intermediary between the client object and an accessible object. The purpose is to monitor the life span of the accessible object and to forward calls to the accessible object only if it is not deleted.
```

**7.** What is the purpose of the `MVC` pattern?

<!-- enter you answer in the space below -->

```
The purpose of the Model View Controller model is to divide related program logic into interconnected pieces. It seperates the views from your controller and model.
```

**8.** What is the job of the `Controller` in the `MVC` Pattern?

<!-- enter you answer in the space below -->

```
The controller is responsible for how the user interacts with the MVC application. It contains flow control logic.
```

**9.** What is the job of the `Service` in `MVC`?

<!-- enter you answer in the space below -->

```
The Service is responsible for mediating communication between the controller and the repository layers.
```

**10.** What is the job of the `Model` in `MVC`?

<!-- enter you answer in the space below -->

```
The Model is responsible for handling the information passed from the database to the user interface.
```
