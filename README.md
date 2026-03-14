# 📘 Java Inheritance Basic Programs
This repository contains basic **Java programs** to understand **Inheritance** concepts.
---
## 🔹 Single level Inheritance
In single level inheritance, the properties of a **single superclass are inherited by a single subclass**.

## 🔹 Multilevel Inheritance

In multilevel inheritance, the properties of a **single superclass are derived by more than one subclass at different levels**.

## 🔹 Hierarchical Inheritance

Hierarchical Inheritance occurs when one superclass is inherited by multiple subclasses at the same level.

Example structure:

        A
       / \
      B   C

Here B and C inherit properties of A.

## 🔹 Multiple Inheritance

Multiple Inheritance occurs when a single subclass tries to inherit from more than one superclass.

Example:

A     B
 \   /
   C
In Java

Java does NOT support multiple inheritance using classes because it creates ambiguity problems.
Diamond Ambiguity Problem:

When multiple inheritance occurs, the compiler becomes confused about which parent method should be used.

Structure:

       Object
       /    \
      A      B
       \    /
         C

If A and B both inherit from Object and C inherits from A and B, then C may not know which implementation to use.

This is called the Diamond Problem (Diamond Ambiguity Problem).

Because of this, Java does not allow multiple inheritance using classes.

## 🔹 Hybrid Inheritance

Hybrid Inheritance is a combination of two or more inheritance types.

Example:

        A
       / \
      B   C
     /     \
    D       E
            F

Hybrid inheritance combines:Hierarchical,Multilevel,Multiple.

Java supports hybrid inheritance only using interfaces, not classes.
---

## 💻 Programs

* 💰 Cash and OnlinePayment
* ✈️ Aeroplane and FighterJet
* 📚 Book and EBook
* 💻 Computer and Laptop
* 📷 Camera and DroneCamera

---

## 🧠 Concepts Used

* Classes and Objects
* Single level Inheritance
* Multilevel Inheritance
* Hierarchical Inheritance
* Multiple Inheritance
* Hybrid Inheritance
