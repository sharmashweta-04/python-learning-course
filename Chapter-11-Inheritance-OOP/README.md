# 📂 Chapter 11 - Inheritance & more on OOPs

<div align="center">

[![Status](https://img.shields.io/badge/Status-Not%20Started-lightgrey?style=for-the-badge)](#)
[![Files](https://img.shields.io/badge/Files-0-blue?style=for-the-badge)](#)

---

This chapter delves into inheritance, code reuse, using parent class methods with `super()`, decorators like `@classmethod` and `@property`, custom getters/setters, and overloading standard operators.

</div>

## 📓 Core Topics Covered
* **Inheritance**: A way of creating a new class from an existing class, inheriting its methods and attributes.
* **Types of Inheritance**:
  * *Single Inheritance*: Derived class inherits from a single base class.
  * *Multiple Inheritance*: Derived class inherits from multiple base classes.
  * *Multilevel Inheritance*: Derived class inherits from a class which itself inherits from another base class.
* **super() Method**: Used to access and call methods from a parent class.
* **Class Method** (`@classmethod`): A decorator that binds a method to the class rather than the object instance (takes `cls` as parameter).
* **@property Decorator**: Creates getter methods to access class properties like attributes.
* **Getters and Setters**: Custom property methods (`@name.getter` and `@name.setter`) to control attribute reading and writing.
* **Operator Overloading**: Defining custom behavior for built-in operators (like `+`, `-`, `*`) on objects using dunder methods (e.g. `__add__`, `__mul__`).

---

## 📝 Practice Exercises (Planned)
* [ ] Create a class C-2d vector and inherit it to C-3d vector
* [ ] Create a class Pets from class Animals and class Dog from Pets (Multilevel Inheritance)
* [ ] Create a class Employee with increment properties using `@property` getters/setters
* [ ] Write a class Complex to represent complex numbers, overloading operators `+` and `*`
* [ ] Write a class Vector representing n-dimensional vectors, overloading `+` and `*`
* [ ] Implement `__str__` dunder method on a custom class
* [ ] Implement `__len__` dunder method on a vector class
