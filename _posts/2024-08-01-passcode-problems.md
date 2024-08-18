---
title: "Passcode Problems"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - statistics
  - security
  - data vizualization
font: 14px
---

I recently came across an [instagram post](https://www.instagram.com/p/C6rb2_kvkHF/?igsh=MWVsZTMzMTh1eGJpaw%3D%3D&img_index=1) with this image: <!--more-->

![Heatmap Data Visualization](/assets/images/passcode_problems_images/big_pin_pic.png)
(source of image: https://informationisbeautiful.net/visualizations/most-common-pin-codes/){font: 10px}

Pretty interesting, I was curious about the way this data was sourced and what methods were used, so I looked a bit into it. The data sourcing, analysis, visualization, and write up are from this [fantastic article](http://www.datagenetics.com/blog/september32012/index.html) by Nick Berry. ![DataGenics article screenshot](/assets/images/passcode_problems_images/datagenics_screenshot.png){: .align-right} I highly suggest checking it out, especially if you’d like to see some great analysis why certain numbers are so likely.

Anyway, I was reading through it and thinking about the 4 digit pin number I am most familiar with in my life and that I see in the lives of so many people around me: my phone’s passcode.

Many people have a 4 digit pin which gives access to their iPhone, along with Face ID of course. But note that the 4 digit pin gives access to all the things you can use Face ID for. Also note that Face ID is not used as a backup if you don’t have the pin, but if you don’t have the face, the pin will get you access anyway. And there are some things (like when an iPhone is turned off and on) for which only the pin will give access.

So I was thinking about these pin number statistics and I was reminded of a news story from a while back, where there was a string of phone thefts at some music festivals. I remember thinking at the time, what a silly theft. I thought the value proposition was terrible because I assumed the thieves were going to try to sell the phones for parts at a low profit. But if they were able to unlock some of them, the value proposition becomes much larger. After seeing these statistics I got to thinking a new question which I think I can now estimate a decent answer to:

If you stole a backpack full of iPhones, how many could you expect to be able to unlock? (assuming they all have 4 digit pin passcodes which are randomly distributed amongst the aforementioned data)

Note: I’m ignoring android smartphones here because they are much less common in my demographic, and in the thefts I’m referring to. Also I know iPhones default to 5 guess attempts before a lockout, so it's simpler for me to have consistent assumptions.

Now to answer the question:

For each iPhone, you get 5 guesses at the passcode before the first lockout

From the data given in the [DataGenics article](http://www.datagenetics.com/blog/september32012/index.html), you could choose the 5 most common pins to guess:

|	| PIN	| Frequency	|
|--------	| -------	| -----------------	|
| 1	| 1234	| 10.713%	|
| 2	| 1111	| 6.016%	|
| 3	| 0000	| 1.881%	|
| 4	| 1212	| 1.197%	|
| 5	| 7777	| 0.745%	|

If you add up those frequencies you get 20.552%.

So in this example you have a roughly 20% chance of unlocking a given iPhone, so for about every 5 iPhones, you could expect to unlock 1!

I think it might be more useful, in the hopes of convincing people to get better passcodes, to focus on that 20% number. I know this is an analysis constrained by certain (not too far fetched!) assumptions, but that number should be jarring!

And if you’re thinking that you use a 6 digit pin for your phone or that you use alphanumeric for your laptop, still please do take a moment to consider that if you passcode has some basis which you thought was kind of random or secret to you, the statistics here imply there is a good chance that it’s not much of a secret really.

[Use good passwords!!!](https://www.cisa.gov/secure-our-world/use-strong-passwords)
