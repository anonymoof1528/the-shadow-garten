---
title: Helpful Guide to using Logarithms in Nuclear Physics
---

Kinda late for this now, but Christian *insisted* on me putting this here
I have some more unfinished business as a result
But this is (cos its short)
Enjoy

# The Helpful Guide to using Logarithms in Nuclear Physics

## An intro to logarithms
Logarithms are really funny. You'll learn them in Year 12, but for the most part, this is all you need to know:

Another way of writing $a^b=c$ is $\log_{a}(c)=b$ 
Another way of writing $\log_{a}(c)$ is $\frac{\log(c)}{\log(a)}$ (where the base is 10)

Why is this? We need to consider the parts of the actual expression to know. $a$ is the base, $b$ is the index/exponent and $c$ is what I call the equivalent (it isn't really important what you call it).

Information can be represented using the base system, which we do all the time (even important for code fr). For the normal numerical system, we use a base of 10, known as the decimal system. Another way is known as the binary system, base 2. There's a whole host of bases, (as long as numbers go, but oddly, all in base 10, think about that hmmm??? jk it's just how bases are shown) hexadecimal, all the works.

The point is that you will have this number multiplied by itself a certain amount of times. How many times? By the exponent. E.g., $2^3=8$, 2 is multiplied three times by itself to get 8.

So, the first statement essentially says "log base $a$ of $c$ is equal to $b$", or in other words, "you multiply $a$ by itself $b$ times to get $c$".

The second statement, on the other hand, delves into a bit more complicated concept known as changing base. This will allow you to calculate things more easily with your scientific calculator. I told you that information can be represented using bases right? This information can be expressed in many different ways using other base systems (but primarily this is only up to the decimal system). So, we can change base $a$ into base 10, which is huge because it's an actual number. The way this is done, as shown above, is dividing the log (base 10) of $c$ (the equivalent) by the log (base 10 again) of $a$ (the original base). The 10 isn't written as a base because it's the standard way that log is used (and also what is in your calculator).

Now onto how this is helpful for Nuclear Physics

## The Nuclear Physics part

Mainly this will only be used when you are attempting to find a value of time (either the total time passed between two readings or the half-life of an isotope). If you've done Nuclear Physics, you know that the general formula is
$$A=A_0(\frac{1}{2})^n$$
and that
$$n=\frac{t_{\text{total}}}{t_{\frac{1}{2}}}$$
If you don't know what those formulas mean, you probably shouldn't be here. It's obvious to see now that it's quite scary to see when you must find one of the times, as it's not even the whole exponent, it's only part of the fraction. But fear not my fellow physics students, as today your worries shall vanish in the fabled and long-awaited

# THE HELPFUL GUIDE FOR USING LOGARITHMS IN NUCLEAR PHYSICS
haha get l'd christian

Anyway
1. Write out everything you have so far (given from the question); you will always have everything (or be able to get everything) except the time value you are trying to find. Let's follow an example for this:
	A sample of a radioisotope has an activity of 520 Bq (or c/s or dps) and decays for 37 years. After this period of time, the radioisotope has an activity of 130 Bq. What is the half-life of the radioisotope?
	
	$A_0=520Bq$
	$A=130Bq$
	$t=37\space \text{years}$
	$t_{\frac{1}{2}}=?\space \text{years}$
	$\therefore n=\frac{37}{t_{\frac{1}{2}}}$
2. Recall the first log law stated. Following this, we should have
	
	$A=A_0(\frac{1}{2})^n$
	$130=520(\frac{1}{2})^{\frac{37}{t_{\frac{1}{2}}}}$
	$(0.5)^{\frac{37}{t_{\frac{1}{2}}}}=\frac{130}{520}$
	$\log _{0.5}(\frac{130}{520})=\frac{37}{t_{\frac{1}{2}}}$
3. But - horror of horrors! - your scientific calculator on has a 'log' button and you can't change the base! Whatever shall you do? Well, recall the next handy log law to use your calculator.
	$\frac{\log(0.25)}{\log(0.5)}=\frac{37}{t_{\frac{1}{2}}}$
	$t_{\frac{1}{2}}=\frac{37}{2}$
	$t_{\frac{1}{2}}=18.5\space \text{years}$

And there you go! I hope you liked the
# HELPFUL GUIDE FOR

just kidding
this was funny
If you guys want more practice questions to use this method just use the same question and change the values (or time measurements) to anything you want, this was just doctored to give a nice answer.