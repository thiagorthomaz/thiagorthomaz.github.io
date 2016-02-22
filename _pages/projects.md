---
permalink: /projects/
layout: projects
title: Projects
description: "Those are some projects made by me, or I've contributed of someway"
tags: projects
published: true
---



# My projects
------------------

Here's a list of my personal project.

## [STPHP](https://github.com/thiagorthomaz/stphp)
When I started the STPHP my main object was use my own Framework into the core of my lato sensu final project in Software Engineering.
Nowaday, I'm using this framework to lean about new code styles, to teste new web technologies, resources and just for fun =).


## TLoS
I’m trying to make a strategy web based game called The lord of Shadows. My idea is make something as The Lord of Ultima. 
So in the game you will have thousands of cities to administrate. In each city you can choose where you will put each building 
and based at the place chosen you will win more points. Ex: If you have a Woodcutter will be better put it close a 
tree to get more points, because if you put close a quarry or in a random place you will get less points. To make the 
players interact with each other my idea is create a ‘card game’, and the players will fight to get the ‘Card of the shadows’,
each card will give some bonus to the players. Ex: There are cards for give more speed for building,
more attack power for the battle units and something else. (I’m wondering yet.).
The game will finish when someone or some team defeat The lord of the Shadows (imagine Sauron) and to defeat him you or your team will need of a strong combination of cards the make your army very strong.
That is a difficult project and will take a long time to be finished. Feel free to help me =).


## [HTMLKit](https://github.com/thiagorthomaz/htmlkit)
That was my first open-source project. When I was growing how a developer.
My objective in this project are help programmers in avoid spaghetti code.
To do that I make a HTML generator with PHP, so you write PHP code and the result is HTML.
Ex:

{% highlight php %}
  $div = new HTMLDiv();
  $link = new HTMLLink("http://www.somesite.com", "Site link");
  $link->setClass("active");
  $div->addElements($link);
{% endhighlight %}

and the result is:

{% highlight php %}
  <div><a href="http://www.somesite.com" class="active">Site link</a></div>
{% endhighlight %}

Very cool, right? Forget HTML, write just PHP!.
