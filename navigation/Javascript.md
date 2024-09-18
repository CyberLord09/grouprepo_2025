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

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Facts</title>
</head>
<body>
    <h1>Random JavaScript Fact</h1>
    <button id="factButton">Show Random Fact</button>
    <p id="randomfactdisplay"></p>

    <script>
        var javascript_fact_list = [
            "JavaScript was created by Brendan Eich in 1995 during his time at Netscape Communications.",
            "JavaScript was originally named Mocha, then renamed to LiveScript, and finally to JavaScript.",
            "JavaScript is a high-level, often just-in-time compiled, and multi-paradigm programming language.",
            "JavaScript has curly-bracket syntax, dynamic typing, prototype-based object-orientation, and first-class functions.",
            "JavaScript is one of the core technologies of the World Wide Web, alongside HTML and CSS.",
            "JavaScript enables interactive web pages and is an essential part of web applications.",
            "JavaScript engines are now embedded in many other types of software, including server-side web servers and databases.",
            "JavaScript supports event-driven, functional, and imperative programming styles.",
            "JavaScript is used for both client-side and server-side development.",
            "JavaScript has a large ecosystem of libraries and frameworks, such as React, Angular, and Vue."
        ];

        function displayRandomFact() {
            var randomIndex = Math.floor(Math.random() * javascript_fact_list.length);
            document.getElementById("randomfactdisplay").innerText = "Fact " + (randomIndex + 1) + ": " + javascript_fact_list[randomIndex];
        }

        document.getElementById("factButton").addEventListener("click", displayRandomFact);
    </script>
</body>
</html>