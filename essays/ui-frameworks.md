---
layout: essay
type: essay
title: "Why Learn UI Frameworks?"
# All dates must be YYYY-MM-DD format!
date: 2022-10-06
published: true
labels: Bootstrap, UI

---

## Bootstrap
Learning Bootstrap has been an two-sided process for me.  On one hand, mundane CSS tasks (like centering an element or setting colors) are automated away by simply adding a class name.  This makes for a much cleaner CSS style sheet and less time stressing over details like why your containers aren't perfectly aligned.  On the other hand, there is a steep learning curve, and using Bootstrap effectively requires that you actualy understand how each element works.  If you do not, this can lead to unexpected behavior and potentially make your project even more complicated.

## Pros and cons
The main benefit of UI frameworks is that much of the styling has been done for you.  This can greatly speed up the process of building a webpage so that you can focus on other tasks.  However, a drawback is that some flexibility is also lost since you must stick to the conventions that the UI framework implements.  For example, in my rebuild of 7 Leaves Cafe's website, I had a difficult time implementing a hover-based dropdown in the navbar using Bootstrap.  When looking further in the documentation, I discovered that it was an intentional design decision by the Bootstrap team to only implement click-based dropdowns.  What I ended up having to do was disable the default Bootstrap behavior and implement my own hover-based dropdown.  Another drawback to consider is that using a UI framework well requires deep knowledge of how each component works.  There have been several instances where I implement several Bootstrap classes only for none of the styling to show up.  This required me to dig deep into the Bootstrap documentation and figure out why I was using their classes incorrectly and how to fix it.

## When to use a UI framework
I believe it is most beneficial to use a framework when you don't have a strict design to follow and can rely on predetermined styling and design choices.  Doing this can greatly speed up the development of a webpage.  However, when webpages become more customized and there is a strict "vision" you need to follow, it may be better to switch back to plain HTML and CSS, and perhaps only use the framework for broad, top-level design.

### An example of a page recreated using Bootstrap:
<img class="img-fluid" src="../img/bootstrap-example.png">
