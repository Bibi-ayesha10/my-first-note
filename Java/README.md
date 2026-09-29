# Java and OOP

## Topic: Classes and Objects

A class is a blueprint that describes what something can have and do.
An object is one actual thing made from that blueprint.

## Key idea

For example, `Student` can be a class. Shabnam can be one `Student` object.
Each student object can have its own name.

## Code example

```java
class Student {
    String name;
}

class Main {
    public static void main(String[] args) {
        Student student1 = new Student();
        student1.name = "Shabnam";

        System.out.println(student1.name);
    }
}
