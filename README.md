# The beginner code guide
Even though there are a lot of programming languages, there are some basic concepts that don't change when you go from one to another. This guide cuts to the chase by teaching you these fundamental concepts in short, compact and digestable snippets.

## Table of contents
1. [Introduction](#introduction)
2. [The basics](#the-basics) 
   1. [Variables](#Arrays)
   2. [Data types](##Data-types)
   3. [Conditionals](#example2)
   4. [Functions](#third-example)
   5. [Arrays and Dictionaries](#fourth-examplehttpwwwfourthexamplecom)
   6. [Loops](#third-example)
3. [FAQ - Frequently Asked Questions](#FAQ)
   1. [What are the `;` at the end of every line for?](##what-are-those-;-for)
   2. [So much about this guide is wrong. Where do you live so I can kill you?](#Complaints-about-technical-inaccuracies)

# Introduction 
You can tell your computer what to do or display by feeding it files that contain instructions. Even though you can't talk to your computer in plain english, you can use something very similar known as a `programming language`. This short guide will be using JavaScript, because you can run JavaScript code directly in the browser.

# The basics

The following sections are ordered by what I personally believe to be the most intuitive order to learn these concepts in, but if you already know how some of these work, you can skip them.

<br/>

> [!NOTE]
> This guide aims to simplify some concepts to make it easier for a beginner to understand them. Because of this, we will have to

## 1. Variables

  
- A _variable_ is like a box you can save information in. This information could be a some text, a number, or even another box. A video game that asks for your name will store it in a _variable_ so that it will remember for later when it is time to add you to the high scores.

    <sub>`playerName` is the name of the variable. `"Bob"` is the text that we save inside of it.</sub>
    ```js
    var playerName = "Bob";
    ```
    Okay. We saved the text inside of the variable _`playerName`_ - Now, how do we display it?
    <sub></sub>
    ```js
    console.log(playerName);
    ```
    When you write the name of your variable, it will turn into whatever you stored inside of it when the program is ran, just like a magic spell.
