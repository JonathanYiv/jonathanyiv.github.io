**Warning:** This is a Work-in-Progress!

**Disclaimer:** I am a student of The Odin Project and as such, I ardently support it.

This post was inspired by the commonly referenced and second top result for googling 'The Odin Project,' [Everyday Utilitarian's Notes on the Odin Project](http://everydayutilitarian.com/essays/notes-on-the-odin-project/).

There are a few reasons for a new post:

1. The Odin Project was created in 2013; that post was written in 2014. It is now 2017; it's outdated. Odin is an [open source project](https://github.com/TheOdinProject/theodinproject) meaning the curriculum, structure, projects, and resources are all subject to change.

2. The author suffers from the [curse of knowledge](https://en.wikipedia.org/wiki/Curse_of_knowledge), wherein he already has 700 hours of self-study __and__ a programming job; therefore, his timeframes for completing lessons are inaccurate and personal to him since he has been exposed to a large amount of the concepts beforehand. Similarly, his recommendations on completing lessons out of order or skipping lessons entirely are in the context of him perhaps already knowing the content.

3. The author didn't strongly advocate paying it forward. If Odin is lacking in some respect, you can always contribute later when you have more knowledge __or__ add additional resources that helped you grasp the material.

It's time for a new look at Odin.

## Structure

Here's how this post is structured:

1. I will give you my frame of reference.

2. Odin is open source and why you should contribute.

3. Step-by-step walkthrough the curriculum, with commentary assuming you're a beginner.

4. Impact of Odin.

5. How long will everything take?

## Perspective

I started Odin without any prior experience, aside from a high school class on Java.

I started with __zero__ hours of self-study.

This references The Odin Project during the timeframe of July 7th, 2017 to [September 21st, 2017].

Your experience with Odin will vary because your perspective going into it will probably be different. 

If you have prior coding experience, you will be able to skip sections you are familiar with and move through the curriculum more quickly.

If your only computing experience only involved checking Facebook and googling, you may have to delve into the additional resources and will move through the curriculum more slowly.

## Contributing

One of the strongest points of Odin is that it realizes that it can't hold all the best learning resources in its own hands.

There will always be a different way to learn for different people provided by different sources.

This strength exists if and only if you pay it forward by fleshing out the material.

### Beginners

You will not know how to contribute until a third of the way into Web Development 101. [[Tutorial]](https://github.com/TheOdinProject/curriculum/blob/master/contributing.md)

You probably don't feel knowledgeable yet, but there are some situations where you should contribute:

1. If a concept didn't make sense to you, the provided resources/additional resources didn't help, and you found another resource that made everything click -- add it in.

2. Typo? Fix it.

3. Broken Link? See if you can find a recent version in the [Wayback Machine](https://archive.org/web/) to update the link, and if not, remove it.

### Intermediate to Advanced

About halfway through Rails, you will find you are able to contribute at a more advanced level. This is great to develop experience working in a team workflow and encountering novel problems.

Check out the [Contributing Guide](https://github.com/TheOdinProject/theodinproject/wiki/Contributing-Guide) for full details.

Check out the [Issues](https://github.com/TheOdinProject/theodinproject/issues) that need help.

Check out what [Projects](https://github.com/TheOdinProject/theodinproject/projects) are being worked on.

## The Curriculum

Follow these simple rules.

If you understand it, move forward.

If you don't understand it, delve into the additional resources.

If you want a stronger understanding, be wary of [rabbit holes](http://www.urbandictionary.com/define.php?term=Rabbit%20Hole) and delve deeper.

Finally, don't just read example code, **type** the example code.

*Be careful that you don't use rabbit holes or wanting perfect understanding as a means of procrastination.*

### Introduction to Web Development

This course is on the chopping block of the curators. 

If you have come to Odin with the intention to learn web development, go ahead and skip to Web Development 101.

If you don't know if web development is for you, peruse through this section lightly to get a good grasp.

### Web Development 101

While you go through this course, keep in mind that Odin will only briefly cover each topic to give you a taste of them.

All of the material that dives deeper into each subject is beyond Web Development 101.

It is good to ensure you understand the high level concepts primarily over the nitty gritty details.

#### Lesson Workflow

The process for each lesson should be like so:

1. Read the brief introduction.

2. Type or write the _Points to Ponder/Learning Outcomes_ down and read them.

3. Complete the Reading/Watching Assignment.

4. If you can answer and understand the questions listed in the Points to Ponder/Learning Outcomes section, move on to the next lesson.


#### Projects

The projects in Odin are meant to be challenging.

So many people give up because they are weak-willed. 

Don't be them.

*Installations:*
You will encounter difficulties in the installations project. Join the [Chat](https://gitter.im/TheOdinProject/theodinproject) and ask for help. For some reason, some outstanding members of the community know exactly how to fix your issues. I don't.


*Google Homepage/Searchpage:*
This is meant to be hard. You were given a lot of information in a closed environment that held your hand. Now you need to put it into practice.

This is what developers do. This is what they call [technical sophistication](https://www.learnenough.com/story).

If you can't make yourself persevere by googling, critically thinking, and problem solving your way through this, you won't be able to make it.

If you get through it, each project going forward will challenge you just the same, but the way you approach the challenge will get better and better.

Here's a hint that applies for every project: start with something very small. For this project, maybe just start with a textbox.


*Sketchpad:*
This is supposed to be hard.

Remember the hint? Always start small. Make a single box appear. Then make another box appear. Etcetera.


*Ruby on Rails:*
Totally confused and wondering what the hell is going on this project? That's OK. Just take in what you can and follow the steps.

It will make sense further along.


*Pair Project:*
I waited a month and a half to find a partner; I never did.

If you are lucky enough to get a partner, get it done. If you wait a few days and no one shows, just go ahead and complete this project.

Make sure you don't just sit here and wait. I was halfway through the next course when I finally got around to this.


### Ruby Programming

Follow the same lesson workflow provided in the Web Development 101 commentary.

You will be building a lot of command line games, namely: Tic-Tac-Toe, Mastermind, Hangman, Connect Four, and Chess.

**Note:** For the Hangman and Chess projects, use JSON as your serializing format. Just trust me. It's the common tongue.

For those of you with exposure to a previous programming language, a lot of the syntax will be peculiar to you, but once you get it, it's a breeze. This section will probably run smoothly besides a few potential conceptual hiccups at File Input/Output, Testing, Data Structures, and Git.

For those of you new to programming, this will probably be the hardest section. Going from not knowing the concepts of programming to knowing is a rough ride. Take it steady and make progress daily and soon you'll be beyond where you can imagine. 


#### File I/O

I recommend delving deeper into serialization and JSON to get a better understanding. JSON is very widely used and is very important. 

A pertinent additional project would be to implement the ability to save/load state in every game you implement throughout the Ruby course.


#### Testing

The resources and lessons on RSpec are limited, at best.

Don't punish yourself for not using TDD, because [TDD is dead](http://david.heinemeierhansson.com/2014/tdd-is-dead-long-live-testing.html). 

**Note:** That doesn't mean don't test, it means don't treat it like a dogmatic religion and feel guilt for 'sinning.' Test what you need to where you can.

For the Connect Four project, don't make the mistake of doing it completely TDD.


#### Git

The Git sections are extremely reading-heavy and lack enough practical application.

Create some repositories and toy around with the different concepts to get a better idea.


#### Computer Science

While this section has seemingly low relation to web development, it is valuable to understand the importance of data structures and algorithms to the field of programming in general, especially for increasing your hireability.

This is probably the hardest part of the Ruby course, but it is worth it.


#### Code Quality

One thing Odin has a gap on is establishing great code quality.

Check out [POODR](http://www.poodr.com/), [99 Bottles](https://www.sandimetz.com/99bottles/), and [Refactoring: Ruby Edition](https://www.martinfowler.com/books/refactoringRubyEd.html) for some great reads on producing outstanding object oriented code.

I recommend reading through these as you move through the course, applying their principles and concepts to each project.

It wouldn't hurt to go back and refactor your initial Ruby projects as well for practice.


### Ruby on Rails

[Pending...]

### HTML5 and CSS3

[Pending...]

### Javascript and jQuery

[Pending...]

### Getting Hired

[Pending...]

## Results

[Pending...]

## Timeframe

[Pending...]