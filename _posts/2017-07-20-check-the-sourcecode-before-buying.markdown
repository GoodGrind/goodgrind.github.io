---
layout: blog-single
title: "Before you buy the sourcecode, check the damn source code!"
date: 2017-07-20 10:41:27 +0100
tags: business technology case-study
main_image: "code_review.jpg"
author: szmaj
---
The best teacher in life is experience. This means that people learn from their mistakes and failures. This story is about a mistake that you should avoid at all costs.

Years before GoodGrind existed, a client of mine had an ERP system that was so old you could see the gray hair and wrinkles at the UI, not to mention the smell of the old framework. The system was developed by an enthusiastic bunch of people who had a good approach for business but -foreshadowing- less than good knowledge in software development. We are talking about years of development from a small group of people who had ideas but not a lot of time to implement them.

Now the client decided to buy the sourcecode for himself to bring the development inhouse. It's a long story, just accept it as it is. This was strongly discouraged by me but politics got in the way and the deal went down.

### The product

I wish I could've had a look on the code before the purchase. The power of my rejection of buying the code would've been burning stronger than a thousand suns!

The code was a mess with incoherent naming conventions, data model, full of basic errors that even a junior developer would not commit. 
The biggest issue was that it was written in an arcane system that was incompatible with any current framework and it was no longer maintained. The code design and the used components were completely untestable which is a major issue in a complex system like this. Every change feels like you walk on a minefield, 1 new feature introduces 3 new bugs in unrelated locations.

If I could've had a look on the source code with their "guidance" without taking it with me, I would have opted to buying a different system in the long run. A new system that is easier to maintain and modify.

### Conclusion

Only buy sourcecode if you have seen it and the developers explained it to you. Check for red flags like no CI server, lack of automated testing or signs of bad coding and antipatterns.

Or just pay for the developers to maintain the damn system without buying it for yourself :)
