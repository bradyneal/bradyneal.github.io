---
layout: post
title: Which causal inference book you should read
subtitle: A flowchart
description: A flowchart to help you choose which causal inference book to read. Also, a few short book reviews.
gh-repo: bradyneal/causal-inference-books
gh-badge: [star, follow]
tags: [resources]
comments: true
permalink: which-causal-inference-book
---

**Last updated:** November 24, 2019

**Disclaimer:** I have only read 4 of the 9 books in the flowchart below. However, I list the other 5 in the flowchart because I think I know enough about them to do so. You can read short reviews of the ones I read below under the "Mini Reviews" heading.

# Flowchart 

![Causal Inference Books Flowchart](/img/books_flowchart.svg)

# Mini Reviews

I review the books below in roughly the order I read them.

### Elements of Causal Inference
This book is fantastic for those coming from a machine learning background. It even has two chapters dedicated to connecting causal inference to machine learning. This book is probably the best book for modern causal discovery (structure learning) techniques. While the term "causal inference" does not include causal discovery in other books, in this book it does. This is because a huge portion of this book is dedicated to causal discovery. And it still gives you a decent foundation in structural causal models (SCMs).

### Causal Inference: What If

This book is the most practical of all of the books I've read. For example, it is the only one that covers the concept known as "positivity" (or "overlap"), which is an important condition that must be satisfied in order to estimate causal effects. It is also the only book of these 4 that actually covers how to estimate the outcome models and propensity score models, which are used to estimate causal effects in practice. In fact, a huge chunk of this book is dedicated to different kinds of estimators that can be used in practice. In case you do not know, Jamie Robins (one of the authors) is a very important figure in epidemiology and causal inference more generally. For example, Judea Pearl credits him with the fact that the adjustment formula was implicit in his 1986 paper (the first time the adjustment formula can be discerned in the literature).

### Causal Inference in Statistics: A Primer

This book is probably the best first book for the largest amount of people. It is a clear, gentle, quick introduction to causal inference and SCMs. Pearl is the first author, and he has made many important contributions to causal inference, pioneering SCMs.

### Causality

I'd only recommend this book to those who want to become expert in SCMs. Similarly, this book is unique in that it is the only book I'd recommend to those who are familiar with SCMs and want to become expert in them. It has a lot of great theory in it. It is often not an easy read. I imagine this would be near unreadable if you came to this book without any knowledge of SCMs or strong motivation to learn more about them. All that said, I think this book is often portrayed too harshly by people online. I suspect that many of these harsh reviews come from people who are not too interested in theory.

# Other Books to Consider

(November 24 update)

I will now list some books that I didn't figure out a way of working into the current flowchart yet. Some will likely be incorporated into future versions of the flowchart. For now, I'll just say a tiny bit about each:

* *Explanation in Causal Inference: Methods for Mediation and Interaction* (VanderWeele, 2015) - This book is the go-to for becoming expert in mediation and interaction. The main part of the book is meant to be readable for a very broad audience, so it is not very technical. However, the appendix can almost be read as its own book, and it contains all the technical details that the technically minded reader might want. Also, this book won the American Statistical Association's "Causality in Statistics Education" Award in 2015.

* *Observation and Experiment: An Introduction to Causal Inference* (Rosenbaum, 2017) - Rosenbaum wrote the "Design of Observational Studies" (2010) book that's in the flowchart above, in addition to another causal inference book he wrote in 2002. From the bit that I've read, my current belief is that this 2017 book is meant to be a much more gentle introduction than his 2010 book. Here's how Rosenbaum describes his view of this book:
> My goal in this book is to present the concepts of causal inference clearly, with reasonable precision, but with a minimum of technical material.

* *Causation, Prediction, and Search* (Spirtes et al., 2001) - The first two authors of this book (Peter Spirtes and Clark Glymour) are the ones who came up with the classic PC (Peter and Clark) algorithm for structure learning of the Markov equivalence class of graphs. Pearl credits the first version of this book (1993) with the introduction of the idea that an intervention corresponds to removing all incoming edges to the intervened node in the graph. Pearl also credits this book with the first publication that made the adjustment formula explicit (as opposed to implicit in Robins' 1986 paper).

* *Actual Causality* (Halpern, 2016) - Joseph Halpern does a lot of work on trying to capture what it actually means for X to cause Y. This might be the main book for understanding what it means for something to be a cause of something else.

* And there are others, of course: for example, Cosma Shalizi's forthcoming *Advanced Data Analysis from an Elementary Point of View* book, *Targeted Learning* (van der Laan & Rose, 2011), and others that I'm not aware of (feel free to post them in the comments!)



