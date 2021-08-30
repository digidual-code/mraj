---
layout: post
title: "BabylonJS with React"
date: 2021-08-29
tags: react babylonjs graphvis
permalink: blog/:title
---

{% comment %} intro {% endcomment %}

The start of a new project often involves a bunch of important decisions. In
the case of web applications this involves selecting multiple parts of the
software stack for front and back end. Selecting parts such as programming
language as well as UI framework can involve trade-offs between ramping up time
needed (for new frameworks), stability, as well as adaptability with upcoming
technologies. I recently needed to pick a software stack for a new project
involving an interactive web application that needs to render graphs embedded
in 3D space. My choice ended with the Typescript-React-BabylonJS stack for the
client side, which seems to be sufficient for now. Each of them improve some
aspects of development and put together  make for a pleasant overall developing
experience.

## Babylon JS

3D graphics have become quite prevalent on web browsers, thanks in no small
measure to modern, sophisticated libraries that take care of much of the
laborious parts of graphics programming. The two most popular libraries for web
based 3D graphics at the moment seem to be threeJS and babylonJS.  While both
have a great showcased capabilities, I went with BabylonJS for my project. The
deciding factor for me came down to BabylonJS' seamless, out-of-the-box
interoperability with the React framework and Typescript. Closer inspection
also revealed a rapidly developing BabylonJS tools ecosystem that seems like
quite convenient to work with as well as fun to play around.

## React

In the past, my web development was quite bare bones involving HTML and
JavaScript, with d3 at most for helping in developing visualizations. While
this approach worked quite well to create prototypes for research development,
the code quickly became difficult to manage. Such rapidly increasing complexity
seems to be a common problem that several web frameworks (e.g. Angular, Vue,
React) attempt to solve.  After playing around with three popular frameworks
Angular, Vue, React, I went with using React for my web application. The main
factors in favor of React for me being its interoperability with other
libraries, modular structure, and somewhat gentler learning curve. Some other features that I found to be a pleasant bonus were auto reloading of page by default, hot module replacement, and of course, the data bindings!



## Declarative 3D Graphics Programming on Web with Types

React and BabylonJS both play a role in abstracting away significant
complexities of developing an interactive 3D web application, with BabylonJS
providing a suite of customizable components for graphics and interactivity
support, and React providing a well structured method and structure to organize
the code.  In conjunction, React and BabylonJS allow us to do 3D graphics
programming on the web declaratively, which is essentially program by
specifying what rather than being explicit about each step (see imperative
programming). This is something that I find remarkable and a testament to how
far web technologies have come over the past few years.

The most delightful part of the stack for me, however, is the type support
thought Typescript that helps catch errors faster by catching type inconstancy
related bugs at compile time as well as provides support to view documentation
for library functions inline. My delight in this aspect of the stack would make
more sense in context of me coming back to web programming after a few years of
mainly programming in C++, which is also strongly typed.

## Conclusion

After exploring different options of the development stack, I believe that
almost all of the combination of the latest frameworks would have eventually
allowed for me to complete the application. The combination that I decided upon
just happens to be most aligned with how I wanted to organize my code and
workflow at the moment. Web technologies are evolving rapidly, possibly only
slightly outpaced with the regard to rate of advancement by machine learning
research. It is an exiting time to be around.


