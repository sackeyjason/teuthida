This project is sunsetted, abandonned, extinguished.

Instead check out http://foundation.zurb.com/emails.html (which inspired this)
---

# Teuthida

## A human workflow for lovely cross-client compatible email templates, with a responsive grid framework.

HTML email is a bastard. The problem is poor CSS support from mail clients. [Just look at this mess](http://www.campaignmonitor.com/css/). There are known techniques to overcome these limitations. You use inline style attributes. You use tables for layout, and don't bother with CSS positioning. You use these old-fashioned ways of coding, to cater for the lowest common denominator.

This is a project to make this process more pleasant.

It uses [jade](http://jade-lang.com/), a templating language with JavaScript logic. If you know HTML, you basically know this already.

## Why does Teuthida use jade?

+ Because typing angle brackets and having to close tags is barbaric
+ To store chunks of CSS as variables which you can use multiple times. Basically, to emulate using CSS with classes
+ To use functions to calculate the customisable grid layout (inspired by the lovely [Semantic Grid System](http://semantic.gs/)).

## Why not use a CSS inliner? And what about Ink?

Storing CSS in variables is an alternative to using a CSS inliner too like [this from Zurb](http://zurb.com/ink/inliner.php). It's faster, as there's no extra copy-paste-compilation step: it's compiled along with all the other jade.

[Ink](http://zurb.com/ink/) is a neat project. Parts of Teuthida are inspired by it, and the basic responsive page layout is based on it.

## To-do

- the proper grid
- instructions
- iterations
