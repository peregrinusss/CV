---
title: Strings in JavaScript
subtitle: How to work with it.

# Summary for listings and search engines
summary: About strings in JS.

# Link this post with a project
projects: []

# Date published
date: '2022-05-21T14:30:00Z'

# Date updated
lastmod: '2022-05-21T14:30:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - JS

categories:
  - Theory

---

## <b>Introduction.</b>
<hr>

A string is a sequence of one or more characters that may consist of letters, numbers, or symbols. Strings in JavaScript are primitive data types and immutable, which means they are unchanging.

As strings are the way we display and work with text, and text is our main way of communicating and understanding through computers, strings are one of the most fundamental concepts of programming to be familiar with.

In this article, we’re going to learn how to create and view the output of strings, how to concatenate strings, how to store strings in variables, and the rules of using quotes, apostrophes, and newlines within strings in JavaScript.

## <b>Creating and Viewing the Output of Strings.</b>
<hr>

In JavaScript, there are three ways to write a string — they can be written inside single quotes (' '), double quotes (" "), or backticks (` `). The type of quote used must match on both sides, however it is possible that all three styles can be used throughout the same script.

Strings using double quotes and single quotes are effectively the same. As there is no convention or official preference for single- or double-

## <b>String Concatenation.</b>
<hr>

Concatenation means joining two or more strings together to create a new string. In order to concatenate, we use the concatenation operator, represented by a + symbol. The + symbol is also the addition operator when used with arithmetic operations.

```
const poem = "The Wide Ocean";
const author = "Pablo Neruda";

const favePoem = "My favorite poem is " + poem + " by " + author + ".";
```

## <b>Variables in Strings with Template Literals.</b>
<hr>

One special feature of the template literal feature is the ability to include expressions and variables within a string. Instead of having to use concatenation, we can use the ${} syntax to insert a variable.

```
const poem = "The Wide Ocean";
const author = "Pablo Neruda";

const favePoem = `My favorite poem is ${poem} by ${author}.`;
```