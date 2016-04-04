---
layout:  post
title:   Creationals Design Patterns
description: "Take a look in what I'm studying about creational design patterms."
category: blogging
tags: [php, dev, architecture]
---

## Introduction

Creational patterns deal with objects creation. They help to make independent of the system how its objects are created.\\
Creational patterns are composed for two main ideas: First, encapsulate knowledge about which concrete classes the system uses and second, they hide how instances of theses classes are created and put it together.\\
The main benefit of use creational patterns are that give you a lot of flexibility in what , who, how and when it gets created.\\
	Creational patterns are very closely and sometimes they are competitors. There cases when you have more than one option, for example both of Prototype and Abstract Factory could be used in some cases and other cases when patterns complement each other as Builder could use Singleton.\\
	Throughout this post I’ll write about five of them and show some code examples, in another time I’ll write about how to combine patterns.\\

#### The five creational patterns are:

* Abstract Factory
* Builder
* Factory method
* Prototype
* Singleton

Now let’s talk a little about each one of them.

### Abstract factory

This factory provide a way to encapsulate the creational form between families of relational objects without specifying their concrete classes.

#### Problem

Consider a factory which make books for a lot of publishers which define author, title, subject and other details. For your code be portable for each different book and publisher, your application should not hard-coded the rules. If you instantiate a specific class for each book, this will make harder to look and change your code later.

#### Solution

We can solve this defining an AbstractBookFactory class. This class will declare an interface for create each basic kind of  book and concrete subclasses that will implement the specific informations as publishers, authors, etc.

![Abstract factory's diagram]({{ site.url }}/assets/abstract-factory.png)

