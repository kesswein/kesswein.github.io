---
layout: post
title: Thoughts on Life
---

So far my partner and I have had little work done, and as of now, the purpose of the Cell handle class still rather confuses me. I understand that due to the fact that the size of the AbstractCell is unknown, given that the children of the AbstractCell may grow larger as more data is added into the private variables. From what I see, though, this just pushes the problem back one threshold where instead of the vector not quite knowing the size of the objects that it contains, it is the handle class that will not know its identity other than that will be the child of an AbstractCell. Some of the available material on the class bindings of C++ helps to make it clear C++ will still be aware of the inherited class that the cell pointer is referring to, given that the AbstactCell class does not have any of the implementation programmed in that would otherwise need to be overriden by dynamic binding which C++ does not provide by default. The other possibly troubling prospect looking ahead is how objects that are derived from an abstract class will be able to access each other's private data, especially if they are of different child classes. It might end up working out due to the fact that alive or dead is part of the AbstractCell's private data, therefore all child classes would have access to it, but things might get dicey when the Fredkin and Conway cells need to start interacting with each other.

Tip of the day: read extensively on the material you are trying to implement if you do not fully understand it, before you begin coding
