---
layout: essay
type: essay
title: "An Overlooked Aspect of Coding"
# All dates must be YYYY-MM-DD format!
date: 2022-09-22
published: true
labels: ESLint

---

## Why follow a coding standard?
Software engineers often emphasize efficiency and robustness as hallmarks of great code, but there is one aspect that is often overlooked: readability.  Code that seems efficient because it is packed into few lines but is also unreadable is of little use to anybody.  Projects are often handed off to different teams, and unclear code makes this transition very difficult.  It also hurts yourself, because when you inevitably have to revisit your code a few months later to make updates, it will be very hard to decipher what you wrote.  One way to help fix this problem is to follow a strict coding standard.  Standardizing the style in which code is written can greatly improve readability through things like bracket placement, variable naming, and line indenting.  It also helps with consistency, so that the same style of code is used throughout the entire project and across different files.  This way, when someone else looks at your code, they do not have to try to adapt to your unique and potentially confusing coding style - they are already familiar with the standard.

My experience with ESLint, one of many coding standardizing tools, has been very positive.  ESLint quickly scans your entire code and gives descriptive messages about things that should be fixed.  It eliminates the need to refer to a document or memorize rules yourself.  ESLint not only comments about code aesthetics, but also about conciseness and efficiency.  For example, unused variables will be highlighted and recommended to be deleted, since those variables will only clutter your code and take up unnecessary computer memory.  It also discourages the use of `var` and recommends `let` or `const` instead, since those variables can have block scope.  I see ESLint as more than just a code formatting tool, and more of a tool to enforce overall best coding practices.
