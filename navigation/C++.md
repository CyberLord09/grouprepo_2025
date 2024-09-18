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



## C++

## Introduction
C++ is a general-purpose programming language created by Bjarne Stroustrup as an extension of the C programming language, or "C with Classes". It has imperative, object-oriented, and generic programming features, while also providing facilities for low-level memory manipulation.

## History
C++ was developed by Bjarne Stroustrup at Bell Labs starting in 1979. The language was designed to be an extension of C, with additional features for object-oriented programming.

## Features
- **Object-Oriented**: C++ supports object-oriented programming, including classes and inheritance.
- **Low-Level Manipulation**: C++ allows for low-level memory manipulation.
- **Performance**: C++ is known for its performance and efficiency.
- **Standard Library**: C++ has a rich standard library, including the Standard Template Library (STL).


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