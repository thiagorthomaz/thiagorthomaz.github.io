---
layout:  post
title:   Quick overview about Design Patterns
description: "Here I will share with you a little resume of my studies about Design Patterns."
category: blogging
tags: [php, dev, architecture]
---

## What is?

Design patterns are a reusable solution for programing problems that is commonly found in a real-world application development. 
“Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, 
in such a way that you can use this solution a million times over, without ever doing it the same way twice” [Alexander et al.].\\
Patterns isn’t a plug-and-play library or class that magically solve your problems. They are templates that have to be implemented in 
the correct situation, so be careful because if you implement a Pattern in the wrong situation or place that probably can be a big problem. 
A Pattern can be a double-edged sword. However, implemented in the right place  at the right situation will be your savior.\\
\\
Patterns have to follow structure:

* **Name:**  Describe the pattern and give us a vocabulary to discuss about it.
* **Problem:** Common context when the problem occur.
* **Solution:** How to solve the essence of the problem. Should identify the classes and objects needed.
\\
\\
They are categorized in three groups:

* **Creational** - Deal with the mechanism of creating objects. In some projects the lead to create a object can be unnecessary complexity.
There are five designs best well known ones:
  * Abstract factory
  * Builder pattern
  * Factory method
  * Prototype
  * Singleton

* **Structural** - Deal with the relationship between the objects. That is one of the most important feature, because these kind of pattern help you to find an easy way to realize dependencies between objects, so became easier implement applications which contain independents class and library. 
The following structural patterns are one of the best well known ones:
  * Adapter
  * Decorator
  * Facade
  * Proxy
  * Composite

* **Behavioral** - Deal with the communication between the objects.
  * These kind of patterns are:
  * Interator
  * Observer
  * Command
  * Strategy
  * Template method

