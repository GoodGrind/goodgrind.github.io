---
layout: blog-single
title: "Congratulation to Norbert for receiving his PhD!"
date: 2017-05-16 10:41:27 +0100
tags: organization
main_image: "sram_phd.jpg"
author: szmaj
---
Let us rejoice and celebrate that our founder and CTO, Norber Sram got his PhD from the Doctoral School of Applied Informatics and Applied Mathematics in Budapest. The title of his thesis is "Assesment and development of fuzzy based and statistical hypothesis analysis based referencial models". Even if you don't understand a word of it, it sounds hard and magnificent at the same time.

Norbert is now floating half a meter above ground and can only be addressed as _God Emperor of Software Development_ but besides that, he is still his humble self :)

### What is the thesis about (it will be short and easy I promise)?

In _expert systems_, most of the logic is `if-then` based 

```
	if event_happened => do_this
OR
	if a > edge_value => do_that
```

This is fine when the boundaries are clear cut. The problem arises when a system doesn't really have hard values defined for these events or statuses. This particular problem is even more prevalent when qualitative results are expected instead of quantitative (_very high, little noisy_ vs _61, 13dB_). Think about the following scenarios:

 - The patient's blood pressure is 132/91. Is it high? (_kinda_ high)
 - The sensor shows a rise in signal frequency. Is it too frequent? (not too frequent to raise an alarm)

Fuzzy logic comes to help! It helps you to define groups and the logic decides **how much** a certain value is a member of that group. 

Example: You have 3 groups for blood pressure values: `low`, `normal`, `high`. The boundary of these groups are `0-105`, `85-135`, `125-999`. You can see that the intervals are overlapping. This allows the system to evaluate your BP of 95 as `normal but a bit low` because it's in both groups.

TODO: Fix the shenaniganz of the text

### So what?

TODO: What was the actual implementation of the theory in the theis?

### How is this relevant for YOU?

TODO: How can this be used for different projects in the market that our customers might be interested in?
