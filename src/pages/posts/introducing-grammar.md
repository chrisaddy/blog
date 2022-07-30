---
title: "Machine Learning Needs a (Unix?) Philosophy"
description: "The near future of machine learning should be boring."
date: "2022-07-29"
hero: "/images/mondrian.jpeg"
tags: ["python", "machine learning"]
layout: "../../layouts/BlogPostLayout.astro"
---

Every day there is a _shiny new thing_ in the world of machine learning. Or maybe it's every 10 seconds. It can feel overwhelming, but it really is a wonderful problem to have too many options. Whether it's in choosing modeling architectures, frameworks, data pipelining tools, libraries for model interpretability, drift detection, logging, visibility...

These tools of course require some amount of gluing together. Sometimes this can even be elegant, but it’s rarely obvious. For the amount of mathematics involved in the field, when it comes to the tools we build, I think we could stand to think about the ways in which our tools interface. This is not a criticism. These tools are software. Software is built under time and resource constraints to solve specific problems. No one team should have to have in their head how every piece of the vast machine learning ecosystem connects. But these things do have to get glued together at some point.

What we need is a Unix Philosophy. There are [several flavors](https://en.wikipedia.org/wiki/Unix_philosophy#cite_note-2), but I like [Eric Raymond’s](http://www.catb.org/~esr/writings/taoup/html/ch01s06.html) best. I don't know that our philosophy needs to be the same as the Unix Philosophy. But it is a fantastic way of thinking, and we could pick worse jumping off points. There are 17 points, all brilliant. I won’t try tackling all of them all at once, but I do want to talk about each in due time. Plus, I kind of want to milk 17 separate blog posts out of one idea because I’m a scoundrel.

In the meantime, I’m going to start putting together these ideas into actual code. At the time of writing, this is the kernel of an idea, but I want to think through these ideas out in the open. Feel free to join over at [hyperprior/grammar](https://github.com/hyperprior/grammar).
