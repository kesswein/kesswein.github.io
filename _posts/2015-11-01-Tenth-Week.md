---
layout: post
title: Darwin halfway
---

So setting up Darwin had an interesting amount of trickiness in figuring out how to make the classes interact upon themselves without having another class do the interaction through the use of getters and setters. This still leaves a fair amount of confusion of what actually constitutes a method as a getter or a setter because a fair amount of the access is still done by way of packing data into return types as a tuple or pair or passing all of the relevant data that a method will need in the method arguments, or even passing the pointers as arguments so that the class can access the other class's variables by working on its pointers. There's such an interesting blend of the use of having an object act upon itself when it's really interacting with its surrounding environment (hop, infect or the various if conditions) that it becomes that it becomes confusing as to whether the object is really acting upon itself or if the surrounding universe is doing the acting by proxy of the object's class methods. 

One particular strength I see in the formatting is that the objects can still access other variables of other objects that are within the same class, making it particularly easier to allow the method of that particular class to do the actions rather than having the overarching Darwin universe do the actions in place given that Darwin has no ability to access those class variables.

Tip of the day: plan in advance how you are going to enact the hardest aspects of the program; if you don't know how your implementation will end up working, it may turn out that your implementation that you have been working on for hours won't work at all
