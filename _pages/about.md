---
layout: about
title: about
permalink: /
subtitle: <a href='https://www.lasige.di.fc.ul.pt/'>LASIGE</a>, <a href='https://ciencias.ulisboa.pt/en'>Faculty of Sciences</a>, University of Lisbon<br/>bpdalmeida (at) fc.ul.pt

profile:
  align: right
  image: bernardo.jpg
  image_circular: false # crops the image to make it circular
  address: >
    <p>Dept. of Informatics - 6.3.29</p>
    <p>Campo Grande, 1749-016</p>
    <p>Lisboa, Portugal</p>


news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---


I am a PhD student at the [Faculty of Sciences](https://www.ciencias.ulisboa.pt)
of the University of Lisbon. Currently, I am working at the
[LASIGE](https://www.lasige.di.fc.ul.pt/) research unit.

My main research topics are programming languages, type systems, and session
types. I am interested in type systems in general, but I am mainly focused on
session types. Session types allow describing structured communication patterns,
and they really shine in the presence of concurrency. Furthermore, through these
sophisticated type systems, one can guarantee, at compile time, the absence of
communication errors. Therefore, I consider that capturing bad communication
behaviours is essential to all concurrent programming languages. 

Currently, I am the lead developer of
[FreeST](http://rss.di.fc.ul.pt/tools/freest/), a functional concurrent
programming language where processes communicate via message-passing. The
language features bi-directional channel-based communication. In FreeST, all
communication is governed by context-free session types.
