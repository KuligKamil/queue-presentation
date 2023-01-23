---
# try also 'default' to start simple
#theme: seriph
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

# Queue 
## features you propably don't know

Kamil Kulig

---
layout: two-cols
---

# agenda

<v-clicks>

* queue definitions
* queue data structure
* queue types
* how to implement queue
* message queue vs task queue vs broker vs backend
* message queue
* task queue
* celery
* examples


</v-clicks>

---
layout: two-cols
---

# queue definition

<v-clicks>

queue is a data structure in programming. 

It is similar to the ticket queue outside a cinema hall, where the first person entering the queue is the first person who gets the ticket


First In First Out (FIFO) rule - the item that goes in first is the item that comes out first.

</v-clicks>

::right::
<div v-click="1">

![img_3.gif](images/beer.gif)
</div>

---
layout: two-cols
---

# git