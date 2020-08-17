# State

> "In information technology and computer science, a system is described as stateful if it is designed to remember preceding events or user interactions; the remembered information is called the state of the system."
> - [Wikipedia](https://en.wikipedia.org/wiki/State_(computer_science))

## Contents

- [Learning Objectives](#learning-objectives)
- [About the Projects](#about-the-projects)
- [Suggested Study](#suggested-study)
- Practice
  - [Isolate](./isolate/index.html)
  - [Integrate](./integrate/README.md)
  - [Exercises](#exercises)
- Sundays & Projects
  - [Week 1](#week-1)
  - [Week 2](#week-2)
- [Class Recordings](./class-recordings.md)
- [Curriculum](https://home.hackyourfuture.be/curriculum) (external)
- [HYF Home](https://home.hackyourfuture.be/) (external)

---

## Learning Objectives

### Isolating JavaScript

- Defining _State_
  - Determining what data is important for a user
  - Separating important data from local variables
- Logging
  - Capture and store a log of all user interactions & state changes
  - Use this log to reconstruct user actions and debug your projects

### Integrating JavaScript

- Data-first development
  - Understanding applications as Data + User Interactions
  - Developing from the "inside" out: planning the data & logic of your app without a user interface
- Rendering DOM Components
  - Render data into DOM elements
  - Dynamically update the DOM to represent the current state

[TOP](#state)

---

## About the Projects

In the previous module you learned to decompose & plan projects, organize your code, and use HTML/CSS/JS to implement simple websites that process user input.  All well and good but there was something missing.  Your projects never "remembered" anything!

Enter: __State__.  This is a fancy programming term to talk about the _data_ stored by your web pages.  Nearly every app you use has state -> message histories, images, profile details, weather reports, ... you name it!  Data is the core of any application.  Just like you learned to write tests to describe your functions and show that they do what they should, you will learn how to use schemas and validation to prove that your program data in fact what you say it is.

Your new projects will be more interesting, but they will also be a more complicated.  The logic will be more challenging, and the data saved in your page will change over time leading to bugs you could never have imagined.

To help you understand and debug your projects you will learn about __logging__ - this is a technique where you store a record of every user interaction, all user input, and each _state change_.  It will take some time before you're comfortable logging your projects. Once you are familiar with this technique you will find that it is helpful way to simplify and understand what is happening in your program.

### Planning your Projects

In this module you'll be flipping everything upside down! In previous modules you learned to develop your projects from the user interface backwards, beginning by planning what a user will see on the screen and how they will in interact with this.  Starting now you will learn to do things from the inside out:

1. __What can a user do on your website?__ Write user stories to describe the user's possible interactions with your site
2. __What data is necessary for these user stories?__  Write a schema to describe & validate your project's data. Try determining what will be the best order to develope these stories.
3. __How does the UI represent *state* and *user interactions*?__ Write a wireframe to describe how the UI will represent the program state for users, and how users can interact with the state.
4. __What code do you need to write?__ Fill out your development strategy with the code you will need to write, and who is responsible for what.

### Separating your Concerns

A working project is not enough! For projects in this module we will expect you to turn in code that is well organized & documented according to it's role.  Your projects should have these directories:

- `/src/logic`: contains any functions and tests, and a README describing what is in each file
- `/src/handlers`: contains the handlers for your app, one per user story.  and a helpful README
- `/src/listeners`: contains the listeners for your app, generally one per user story, and a helpful README
- `src/views`: contains the functions your app uses to render data for the UI
- `src/init.js`: contains the code to render your initial UI and log the initial state (_optional_)
- `src/data.js`: contains your initial state
- `src/log.js`: contains the initial empty log for your project.  For now, just an empty array
- `style.css`: contains the CSS for your web page and any helpful comments
- `index.html`: contains the initial DOM for your user interface & requires all scripts
- `README.md`: describes what your project does & how to use it.
- `development-strategy.md`: a file containing your team's development strategy.
- `user-stories.md`: a file containing suggested user stories

Your project will contain one more directory called `/lib`, but there is nothing for you to write in here. This folder will contain dependencies for your project. Feeling motivated? take a look through these files to try and understand them!


[TOP](#state)

---

## Suggested Study

- [What is state and why should we care about it?](https://dev.to/codeartistryio/what-is-state-and-why-should-we-care-about-it-4o95)
- [/integrate/stepped-and-separated](./integrate/stepped-and-separated) (code to study)
- > more links coming soon

[TOP](#state)

---

## Exercises

Exercises for solo-study.  We won't be checking these exercises unless you ask us to look them over, your learning is in your hands.  Take a look through these and find the ones that help the most, the rest will be here for you later!

> To be announced Monday after class

[TOP](#state)

---

## Week 1

The focus of week 1 is storing important data in an object called _state_, and logging all user interactions with this data.

### Prep Work

> before class

- [Isolate](./isolate/index.html)
  - Copying Arrays and Objects
  - Application State (examples)
- [Integrate](./integrate/README.md)
  - Application State (examples)

### Lesson Plan

> during class

#### Isolate

- [Application State](./isolate/index.html) (examples & exercises)

#### Integrate

- [Application State](./integrate/README.md) (examples & exercises)

### Project

> after class

This week's project is to write a JS Quiz.  You'll be given:

- [Starter code](https://github.com/HackYourFutureBelgium/state-project-js-quiz)
- [An initial state](https://github.com/HackYourFutureBelgium/state-project-js-quiz/tree/master/src/data.js)
- [A list of possible user stories](https://github.com/HackYourFutureBelgium/state-project-js-quiz/tree/master/user-stories.md)

The rest is up to you!

#### Checklist

```md
- [ ] [repo](https://github.com/_/_) with a complete README
- [ ] [live demo](https://_.github.io/_)
- [ ] [development-strategy](https://github.com/_/_/tree/master/development-strategy.md)
- [ ] [At least 6 initial quiz questions](https://github.com/_/_/tree/master/src/data.js)
- [ ] [A project board](https://github.com/_/_/projects/X)
- [ ] [One branch per step in `development-strategy.md`](https://github.com/_/_/network)
- [ ] [One closed issue per task](https://github.com/_/_/issues?q=is%3Aissue+is%3Aclosed) (you can have more than task per development step!)
- [ ] [One closed PR per task issue](https://github.com/_/__/pulls?q=is%3Apr+is%3Aclosed)
```

[TOP](#state)

---

## Week 2

The focus of week 2 is learning how to render data into DOM elements to create interactive user interfaces.

### Prep Work

> before class

### Lesson Plan

> during class

#### [Isolate](../isolate/index.html)



#### [Integrate](../integrate/README.md)



### Project

> after class


[TOP](#state)
