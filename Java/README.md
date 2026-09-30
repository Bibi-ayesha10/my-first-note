# Java and OOP

## Topic: Classes and Objects

A class is a blueprint that describes what something can have and do.
An object is one actual thing made from that blueprint.

## Key idea

For example, `Student` can be a class. Shabnam can be one `Student` object.
Each student object can have its own name.

## Code example
class Student {
    String name;
    int semester;

    Student(String studentName, int studentSemester) {
        name = studentName;
        semester = studentSemester;
    }

    void introduce() {
        System.out.println("Hi, I am " + name);
    }
}
