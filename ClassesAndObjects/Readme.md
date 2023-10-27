## What is mean by an Class ?

-  A class is a blueprint or a template for creating objects. It defines the structure, behavior, and attributes that its objects will have. In Java, classes are declared using the **class** keyword.

#### Example :-

```java

public class MyClass {
    // Fields (attributes)
    int x;
    String name;
    
    // Methods (behavior)
    public void doSomething() {
        // Code to perform some action
    }
}

```

- **Fields (Attributes)** : Fields are variables declared within a class. They represent the state or attributes of an object. In the example above, **x** and **name** are fields.

- **Methods (Behavior)** : Methods are functions defined within a class. They define the behavior or actions that objects of the class can perform. In the example above, **doSomething()** is a method.

- **Access Modifiers** : You can use access modifiers like **public, private, and protected** to control the visibility of fields and methods. For example, a **private** field can only be accessed within the class.


## What is mean by Object ?

- An object is an instance of a class. It is created based on the blueprint defined by the class. You can think of a class as a cookie-cutter and objects as the cookies you make using that cutter

```java
MyClass myObject = new MyClass(); // Creating an object
```
- **Instantiation** : To create an object, you use the new keyword followed by the class constructor. In this case, myObject is an instance of the MyClass class.

- **Accessing Members** : You can access the fields and methods of an object using the dot notation. For example:

```java

myObject.x = 10;           // Accessing a field
myObject.name = "John";    // Accessing a field
myObject.doSomething();    // Calling a method

```

## What is mean by an Constructor ?

- A constructor is a special method in a class used to initialize objects. When an object is created, the constructor is called automatically. If you don't define a constructor, Java provides a default constructor with no arguments. You can also define your own constructors.

#### Example 

```java
public class MyClass {
    int x;

    // Constructor with no arguments
    public MyClass() {
        x = 0; // Initialize the field
    }

    // Constructor with an argument
    public MyClass(int initialValue) {
        x = initialValue;
    }
}
```