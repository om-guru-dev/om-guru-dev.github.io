---
layout: post
title:  "Session 02 Preparation Materials"
date:   2015-04-04 17:00:00
categories: general setup
author: Prabhas Pokharel
---

Session 1 was mostly an introduction, and preparation towards session 2 will take you even deeper into Clojurescript. I'll list the materials to go through first, and add some detailed notes afterwards as to certain sections you can skip within the preparatory materials. You don't have to skip these; I just think they may be a little complex for now.

Repeats From Last Time (in case you haven't finished):
 
 * [Clojurescript Koans](clojurescriptkoans.com)
 * [Clojure for the Brave and True, "Do Things" chapter](http://www.braveclojure.com/do-things/)
New:
 
 * Go through David Nolen's [Clojurescript tutorial in LightTable](https://github.com/swannodette/lt-cljs-tutorial). David Nolen is the author of both clojurescript and om.
 * Go through my own [More on Clojurescript and Functional Programming](https://github.com/om-ninja/om-tutorial/wiki/0.5.-More-on-Clojurescript-and-Functional-Programming)

Remember to type things in yourself, copy/paste will be easy, but you won't learn that way.

Notes on things you can skip for now:

Brave and True / Do Things:
 
 * Skip the section on quoting

LightTable tutorial
 
 * `loop` / `recur`: You can skip the part on loop / recur. We actually won't go very deep into recursion in the class.
 * `multimethods`
 *  Finally, you can finish when you get to PROTOCOLS. No need to go through protocols, types, and records, unless you want to.

Clojurescript Koans:
 
 * When you get to conditionals, like conditionals#5, you will want to copy / paste that code into LightTable and format it according to your needs. Lots of stuff starting even with functions gets easier to understand if you indent the code properly. If you do ctrl-space in LightTable, you can search for "Smart Indent" to have LightTable indent code for you.
 * **Runtime polymorphism** Feel free to skip this section, it is a bit advanced. To skip, go directly to [lazy sequences#1](http://clojurescriptkoans.com/#lazy-sequences/1)
 * You can skip De-structuring, but don't skip it in the LightTable tutorial. This is just because it is a bit tedious. Go to [atoms#1](http://clojurescriptkoans.com/#atoms/1) instead.
 * FINALLY, you can be done if you get to atoms#5 There isn't much left, so go to the finish if you want to, but you don't need to.