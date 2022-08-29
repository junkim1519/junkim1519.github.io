---
layout: project
type: project
image: img/sudoku.png
title: "Sudoku Solver"
date: 2021-12-01
published: true
labels:
  - Python
  - Recursion
  - GitHub
summary: "A program that solves any Sudoku puzzle"
---

<img class="img-fluid" src="../img/sudoku-banner.png">

This program uses recursion to solve any Sudoku puzzle by brute force. The puzzle starts at the first empty cell and tries all possible numbers 1-9. If a number is valid, it moves on to the next cell. If the program hits a dead end (no valid numbers can be entered in a cell), it will backtrack and try again with the next number.

Although inefficient, this program does demonstrate the power of recursion and the ability to solve complex problems with relatively few lines of code.

Source: <a href="https://github.com/junkim1519/sudokuSolver"><i class="large github icon "></i>junkim1519/sudokuSolver</a>
