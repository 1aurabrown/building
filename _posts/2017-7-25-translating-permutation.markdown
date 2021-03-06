---
title: Translating Permutation
date: 2017-07-25 12:00:00 Z
categories:
- Case Study
tags:
- featured
layout: post
image: https://d2w9rnfcy7mm78.cloudfront.net/1149954/original_a5d4bd6dc0e464c50859974efe609b71.png
author: "Bryce Wilner"
description: "Permutation in the work of Samuel Beckett and Robert Grenier."
---

<img src="https://d2w9rnfcy7mm78.cloudfront.net/1149954/original_a5d4bd6dc0e464c50859974efe609b71.png">

---

A black-stroked, white-filled table sits centered on the light-gray background of a browser window. Below the table in a slightly darker gray: two bevelled, rectangular buttons bearing the words “Back” and “Next.” Upon clicking the latter, sentence fragments, letters, lists, names, nouns, and numbers populate the table. All of the text is set at a fixed point size in black Courier. Pressing the “H” key changes the button labels to two numbers that, when added together, always equal five-hundred. To refresh this page is to completely reorder the text; it’s unlikely that the reader will experience it in that configuration again.

The website I describe is a poem that was originally published in 1978 on a deck of five-hundred 5 × 8” index cards. The poet Robert Grenier wrote _Sentences_ such that the reader could shuffle and experience it in any order, suggesting vast lexical potential by omitting the one asset that traditionally assures a book its bookness: the binding. Grenier released the piece through the Cambridge, Massachusetts-based publisher Whale Cloth Press in a pretty, unfoldable box. Whale Cloth now offers a few low-res JPEGs of the original edition on their website, but they no longer sell it. Rather than crowdfunding what would be an expensive reprint, or attempting a print-on-demand-style reissue, the press translated the piece into HTML, CSS, and Javascript and published it for free on their [website](http://whalecloth.org/grenier/sentences_.htm). This translation of the work has been online since 2003.

![](https://d2w9rnfcy7mm78.cloudfront.net/1147311/original_b49d0c77f78a0d2722dca8094662f84e.gif)
Robert Grenier, Sentences [1978] (Cambridge: Whale Cloth Press, 2003).

I learned about _Sentences_ in college; I would eventually find out that it’s a late-ish entry in an esoteric but influential literary canon known as “book in a box.” Grenier—along with artists and writers like B.S. Johnson, Alison Knowles, Eduardo Paolozzi, and Marc Saporta—anticipated in his work a sense of textual nonlinearity and randomness that the Internet now makes abundantly available. For years I’ve cited _Sentences_’s self-reflexivity when talking about my own graphic design and publishing work, but only this summer came across the original print edition in the Beinecke Rare Book and Manuscript Library at Yale. Any other surviving copies likely live in similar research libraries or in the homes of collectors.

The 2003 version of _Sentences_ is one example of an archiving and publishing tendency that I call “Screen Translations of Permutational Print Texts.” It’s a cumbersome designation to be sure, but it conveys three indispensable bits: 1) These (usually web-based) publications are translated to screen because they deal with permutation. 2) On most occasions, the original permutation occurred in physical space. 3) They are translations and are therefore imperfect. 

<iframe class="arena-iframe" width="100%" height="2090" src="https://www.are.na/bryce-wilner/screen-translations-of-permutational-print-texts/embed"></iframe>

In mathematics, “permutation” refers to the act of changing the order of a set of units (abc, cba, bac, et al.). If one experiences the concept of the book—a finite set of letters, words, pages—as a world, it follows that one can see every iteration of that world realized eventually and efficiently through random permutation. Samuel Beckett established such a set while writing _Sans_ in 1969, which he translated into an English version titled _Lessness_ one year later. _Lessness_ reads like a dense combination of apparent verbal randomness, and for good reason. Beckett indicated that the structure of the text was determined by randomly drawing sentence-inscribed pieces of paper out of a container on two separate occasions (each sentence occurs once in the first and once in the second half of the book). From 2000–2017, Mads Haahr and Elizabeth Drew, respectively a computer scientist and an English researcher at Trinity College, produced and maintained a research tool titled [_Possible Lessnesses_](https://www.are.na/block/880620) that allows one to generate alternate versions of _Lessness_ according to the rules originally used by Beckett. In a [paper](https://www.are.na/block/1047634) accompanying the project, Haahr and Drew distinguish between two types of random numbers: those created by pseudo-random number generators (PRNGs), or algorithms designed to mimic randomness, and those created by true random number generators (TRNGs), which generate their randomness with help from an outside source, such as variations in atmospheric noise. 

The authors write, “What separates the two approaches is determinacy. Whereas the best PRNGs produce numbers that are virtually indistinguishable from those generated by TRNGs, any string of numbers produced by the former is essentially predetermined and can be replayed given the starting conditions. The randomness generated by TRNGs originates in physical processes and is akin to rolling a die or drawing tickets out of a hat.”

It seems to me that the 2003 screen translation of _Sentences_ can be read as the PRNG to the 1978 print version’s TRNG. I risk introducing heady mathematical analogies that are outside the scope of this essay (and the limits of my understanding of computer science) to suggest that Whale Cloth’s screen translation might be theoretically and counter-intuitively _less_ random than the original box of index cards since it’s difficult for computers to truly produce the randomness inherent in the simple act of, say, shuffling the deck. Additionally, translating a permutational text from a print medium into a browser leaves behind behaviors such as turning over cards, arranging them side-by-side, overlapping, and repeating, all of which can inform the speed and read of a text. It is worth noting that in a browser, however, these shifts in interactivity and participation lead to distribution and cost efficiency, as well as an immediacy that is less rearranging a kit of parts and more an advance through a world that renders bit by bit onmouseclick.

This is not to proclaim one medium superior to another; I mean instead to draw similarities and distinctions between what is often seen as a reductive binary of physical or digital media. Screen Translations of Permutational Print Texts are useful not only for their distributional, archival, and educational benefits, but because they reinforce what made these works remarkable at their time of release: that despite recognizing the limits of their media, they offer strategies for working around and past those limits. Observing the aspects of a text that remain constant as it is translated across various physical and digital interfaces into time may very likely give readers a better understanding of its essence. Even so, that the randomness of _Sentences_ may be less at home in the browser space it anticipated than in the print format it pushed beyond is a fascinating and sad thought through which I imagine I’ll be working for the foreseeable future.

![](https://d2w9rnfcy7mm78.cloudfront.net/1147310/original_65991f44379e54e2c655dac190303c8a.gif)
Bryce Wilner, [_Shuffle_](http://shuffle.brycewilner.com) (documentation), 2017.

---

_[Bryce Wilner](https://www.are.na/bryce-wilner) is a graphic designer currently based in New Haven, CT._
