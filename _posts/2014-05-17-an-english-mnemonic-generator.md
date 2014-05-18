---
layout: post
title: "An english mnemonic generator"
description: ""
category: demo
tags: [nlp, markov chains, english]
---
{% include JB/setup %}
Have you ever seen any of those clever guys who are able to recite endless series of digits of number Pi? Sometimes they do it with mnemonics : sentences where each word is the same length as an according digit of Pi number: *"How I wish I could calculate pi.".* (3.141592) The tonnes of mnemonics like that do exist (see [piphilology](http://en.wikipedia.org/wiki/Piphilology)). Now you can do the trick: senseless poetry is a lot of easy to remember than digits. But the question is how on earth someone was able to write such sentences?

I can suggest you the solution: [mnemonic generator](http://enwiz.jelasticloud.com/#memento). Just allow this simple toy to crunch your series of digits and it might provide you a suitable mnemonic, as that one: *"Now I have a child condemned to always think"* (3.14159265).

How does it works? Wow, it's so simple. Let's assume a table exists which for each couple of words lists the words that can plausibly follow them. It makes the trick: for each next position we can choose the word of required length. A bit tiresomly for a human, but easy for a machine: they never stops thinking until get a profit.

With [sentence generator](http://enwiz.jelasticloud.com/#generate) you can try to do it on your own choosing next word from a variety of prompted ones. Do you have other requirements instead of lengths of the words? You can write a quirk phrase: *"She saw someone standing silently."* Or an acronym: *"We Are The Cruel Hands."* (for "WATCH"). Or you can even write something sensible. I hope it gives you a chance to get the bridge between English as a language and English as a part of your personality. Enjoy the puzzle :).

This toy, [EnWiz](http://enwiz.jelasticloud.com) uses a vocabulary more than 85000 words that forms 4000000 trigrams. But you can try your own set, [getting the sources of EnWiz here](https://github.com/electricmind/enwiz).

...but if someone asked me "how far is it going to lead us?", I would answer: "as far as [Trurl's Electronic Bard in famouse novel of Stanislaw Lem](http://sfbay-anarchists.org/wp-content/uploads/2012/05/Trurls-Electronic-Bard.pdf) does".
