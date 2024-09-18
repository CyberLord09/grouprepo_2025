---
layout: page
description: 
type: 
comments: True
---

<table>
<tbody>
    <td> 
    <a href="/grouprepo_2025/navigation/Python">Python</a>
     </td>
     <td> 
    <a href="/grouprepo_2025/navigation/C++">C++</a>
     </td>
     <td> 
    <a href="/grouprepo_2025/navigation/Java">Java</a>
     </td>
     <td> 
    <a href="/grouprepo_2025/navigation/Javascript">Javascript</a>
     </td>
      <td> 
    <a href="/grouprepo_2025/navigation/Ruby">Ruby</a>
     </td>
     </tbody>
</table>

## Javascript

## Introduction
JavaScript is a high-level, often just-in-time compiled, and multi-paradigm programming language. It has curly-bracket syntax, dynamic typing, prototype-based object-orientation, and first-class functions.

## History
JavaScript was created by Brendan Eich in 1995 during his time at Netscape Communications. It was originally developed under the name Mocha, then renamed to LiveScript, and finally to JavaScript.

## Features
- **Dynamic Typing**: JavaScript is dynamically typed, meaning variable types are determined at runtime.
- **Prototype-Based**: JavaScript uses prototypes instead of classes for inheritance.
- **First-Class Functions**: Functions in JavaScript are first-class objects.
- **Event-Driven**: JavaScript is often used for event-driven programming, especially in web development.


<br>
<br>

<button id="jokeButton">Get a Random Accounting Joke</button>
<p id="jokeDisplay"></p>

<script> 
  var accounting_joke_list = [
      "Why did the accountant cross the road? To bore the people on the other side.",
      "What do accountants do when they're constipated? They work it out with a pencil.",
      "Why don't accountants read novels? Because the only numbers in them are page numbers.",
      "How does an accountant stay out of debt? He learns to act his wage.",
      "Why did the accountant break up with the calculator? It couldn't handle his complex calculations.",
      "Why did the accountant stare at his glass of orange juice for three hours? Because on the box it said 'concentrate'.",
      "Why did the accountant bring a ladder to work? To reach the high interest rates.",
      "Why did the accountant get promoted? Because he knew how to balance his work and play.",
      "Why did the accountant go broke? Because he lost his balance.",
      "Why did the accountant get a job at the bakery? Because he was good at making dough.",
      "Why did the accountant get a job at the zoo? Because he was good with cheetahs.",
      "Why did the accountant get a job at the bank? Because he was good at counting on it.",
      "Why did the accountant get a job at the library? Because he was good at keeping books.",
      "Why did the accountant get a job at the circus? Because he was good at juggling numbers.",
      "Why did the accountant get a job at the restaurant? Because he was good at serving up the numbers.",
      "Why did the accountant get a job at the gym? Because he was good at working out the numbers.",
      "Why did the accountant get a job at the hospital? Because he was good at taking care of the accounts.",
      "Why did the accountant get a job at the school? Because he was good at teaching the numbers.",
      "Why did the accountant get a job at the farm? Because he was good at counting the chickens before they hatched."
  ]
    function displayRandomJoke() {
        var randomIndex = Math.floor(Math.random() * accounting_joke_list.length);
        document.getElementById("jokeDisplay").innerText = "Joke #" + (randomIndex + 1) + ": " + accounting_joke_list[randomIndex];
    }

    document.getElementById("jokeButton").addEventListener("click", displayRandomJoke);
</script>