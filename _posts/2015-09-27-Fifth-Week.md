---
layout: post
title: K, Not as easy as I thought
---

Last week, I said that I had all of the tests of Voting.c++ running smoothly and that the entire algorithm was working smoothly. When I arrived back at the lab a few days later I would discover how horribly wrong I was. It turns out that just by having 6 simple tests passing does not mean the program is working as intended. In fact, even in the logic of those 6 tests, the tests were only coming to the right answer by accident and might have arrived at a different candidate if the candidates were listed in a different order. Every time a bug was patched up, 3 more would take its place including a rather embarrassing one of only reading the first digit of a 2 digit number (oops) , situations so many are sure to be familiar with. It didn’t help that the bizarre rules from last time (projects due at 10 pm instead of at midnight) appeared once again. It turns out that because we had one commit after the log was created, the assignment will be taken as one day late. Seriously, a log missing a single update warrants taking 20% off?
With all that off my chest, I would like to say that I’m glad to see vectors and lists getting some in depth look. I found vectors to be a very useful tool for developing the Austrailian voting algorithm due to their ease of access and adding on new elements.
Tip of the day: Double check the requirements. Then triple check them.
