# Pyblob Tutorial

## Skills Assessed
- Solving problems with… 
    - Importing modules 
    - Creating Classes
    - Create instances 
    - Using inheritance
    - Overriding methods 
    - Using dunder methods

## Goals
Python is such a versatile language. We can create APIs, do data analysis, build web apps, and create games! In this project, we will use OOP to build an animation in pygame. 

**What is pygame?**

[Pygame](https://www.pygame.org/wiki/about) is a library that allows developers to create games using Python.
To provide a better visual picture of OOP, we’ll be creating an animation of blobs! 

<iframe src="https://giphy.com/embed/9DFDu1xmCeXvil0FcR" width="252" height="280" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/9DFDu1xmCeXvil0FcR">via GIPHY</a></p>

## Project

Pyblobs is a **2-day project**. The first day you will make an animation in pygame by completing a tutorial independently. The second day we will review the content of the tutorial together in round tables and then you will work in pairs to extend and enhance your animations.


## Tutorial

We will follow this tutorial on [pythonprogramming.net](https://pythonprogramming.net/object-oriented-programming-introduction-intermediate-python-tutorial/). 


## Initial Set Up

To create our game we will use **repl.it**, a browser based IDE. Repl allows developers to create and run mini applications in the browser. We highly suggest [creating an account](https://repl.it/signup) with Repl using your github credentials. This will allow you to create repositories and commits to Github using Repl's interface. 

For a more collaborative experience, we also suggest using repl's multiplayer feature to have you and your partner edit on the same repl together. To use multiplayer mode, click "Share" on the top right corner, a pop-up window should appear with the invite tab open. Type in your partners username and click 'invite'. 


## Getting Started with Pygame 

1) Download the Pygame library in the packages section. 
2) Once you see a `poetry.lock` and `pyproject.toml` file appear in the Packager files section on repl.it you are ready to start the tutorial!

## Tutorial
We will complete 5 lessons from this [tutorial](https://pythonprogramming.net/object-oriented-programming-introduction-intermediate-python-tutorial/) as outlined below.

### Create one single moving blob
- [Introduction to OOP](https://pythonprogramming.net/object-oriented-programming-introduction-intermediate-python-tutorial/)
- [Creating Environment for Object with Pygame](https://pythonprogramming.net/creating-pygame-environment-intermediate-python-tutorial/)

### Create many moving blobs
- [Many blobs - OOP](https://pythonprogramming.net/many-blob-objects-intermediate-python-tutorial/)
- [Blob Class and Modularity OOP](https://pythonprogramming.net/class-object-modularity-intermediate-python-tutorial/)
- [Inheritance - OOP](https://pythonprogramming.net/inheritance-object-oriented-programming-intermediate-python-tutorial/)

### Optional Reading (No more blobs, but some fun python OOP concepts)
- [Decorators in Python](https://pythonprogramming.net/decorators-intermediate-python-tutorial/) 
- [Special Methods, OOP, and Iteration Python](https://pythonprogramming.net/special-methods-iteration-intermediate-python-tutorial/)

<!-- prettier-ignore-start -->
### !challenge

* type: short-answer
* id: be417a18-aed2-47a0-87ff-ff53c2bdf5a2
* title: Reflection Question 1: check_bounds

##### !question
At the end of [Blob Class and Modularity OOP](https://pythonprogramming.net/class-object-modularity-intermediate-python-tutorial/), the author has this to say about the check_bounds method: "Now, the programmer can decide to use it or not. You could also give some sort of argument in the move method, where, if `True`, then boundaries would be enforced."

Consider how you would implement this optional enforcement of boundary checking, and record your thoughts here.
##### !end-question

##### !answer
/*+/
##### !end-answer

##### !placeholder
Input your answer here
##### !end-placeholder

### !end-challenge
<!-- prettier-ignore-end -->

<!--prettier-ignore-start-->
### !challenge

* type: short-answer
* id: 5d71a7a1-872d-4b4b-9744-4ced52d0985b
* title: Reflection Question 2: `move` vs `move_fast`

##### !question
The author changes the name of the `move` method to `move_fast` in the child class `BlueBlob`. Is this name change necessary? What would happen if we left it as `move`?
##### !end-question

##### !answer
/*+/
##### !end-answer

##### !placeholder
Input your answer here
##### !end-placeholder

### !end-challenge

<!-- prettier-ignore-end -->
