---
title: A Robot For Every Human
date: 2020-03-30T04:10:32.000+05:30
template: post
draft: false
slug: a-robot-for-every-human
category:
- Essay
tags:
- Automation
- AI
- Domain Specific Language
description: 'At MayaHQ, we’re trying to build a bot that will one day replace us
  – a general machine intelligence. Here is our angle of attack. '
socialImage: "/media/image-0.jpg"

---
At [Maya](http://getmaya.co/), we’re trying to build a bot that does everything for us – a general machine intelligence.

We think modern machine learning doesn’t yet have a way to do it. You can optimise it to do one thing well, so it can play superhuman Starcraft or Chess, but for generality, we need to go further – optimise generality itself.

The fundamental problem with current methods is that they do less from more. Feeding a lot of initial samples makes today’s bots do one narrow skill well. We want to create a process which will help build bots to do many complex tasks by rearranging the same few primitive building blocks.

A good example of such a more-from-less process is the language I’m using to write this. The Oxford dictionary has just 170,000 words that have evolved over years – you can reuse them to build sentences, many sentences make a paragraph and so on. Language is important because it has the symbols we use to think.

To note, around 47,000 words from the Oxford Dictionary have become obsolete. This is because the natural dynamics of language are like that of a free-for-all marketplace – the useful words and phrases stay on, while the useless ones quickly slip out of use.

Our intuition is that a more-from-less process to making general machine intelligence should work like language does. What would this look like ? It would have, **One**, a marketplace mechanism to reward the primitive building blocks and bots that work well and weed out the ones that don’t, **Two**, a domain specific language that encodes how primitives are arranged together and, **Three**, a way to learn this language to auto-generate new bot flows on the go

To solve the first two problems, we built Maya. The third is something we intend to figure out along the way, but we know of which there is atleast one precedent – auto-complete for the English language. **One**, Maya is a marketplace that allows individuals & firms to make, run & sell reusable bot primitives (analogous to words) arranged to make useful bot flows (sentences), all using our cross-platform tool. **Two**, all bot flows use the Maya flow-based language to describe how different primitives are wired together. These two are hard problems on their own, but we suspect that with enough bots built using Maya and hosted on our marketplace for users to benefit from – our mission is _a bot for every human_ – we could solve problem **Three** too. This would hopefully lead to a bot that “thinks ahead” (like auto-complete does) in the Maya language to generate bot flows that completes many complex tasks by rearranging the same set of primitives from the marketplace.

We still have a long way to go, but we think we have something interesting here. Stay tuned.