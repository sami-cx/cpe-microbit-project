# CPE micro:bit Term Project

Term project for students in the CPE 1040 course at MSUD, Fall 2018.

## Assignment

Design and implement some application of the [micro:bit](https://microbit.org/) educational computer. It can be a new design of your own or an already existing design from the Web.

### Language requirement

The implementation has to be in [MicroPython](https://microbit-micropython.readthedocs.io/en/latest/) (the version of Python that works on the micro:bit). 

**Note:** It is perfectly acceptable to take a project implemented in JavaScript/Blocks and rewrite it in MicroPython.

## Submission

### 1. Github

Fork and clone this directory and submit the URL of your fork (remote) on [Canvas](https://canvas.instructure.com/courses/1397722/assignments/10046266?module_item_id=20700270).

### 2. Individual

You can collaborate with one or two team mates on the design, implementation, and testing of the project, but you have to have *your own* separate Github repository and make an *individual* submission on Canvas.

### 3. Due date

**Sun, Dec 2, 2018, by 23:59**

**Note:** You can submit your URL at any time before the deadline on Canvas. Only your latest commit on Github earlier than the deadline will be evaluated.

### 4. Project report

Write the project report in your README using the template provided below. 

**Note:** Projects without reports will receive **0 points** for the whole project.

### 5. Project demo

The project has to be demonstrated by the team in the lab period on **Wed, Nov 28**. Presentation slides are *optional* but will be noted in the evaluation of your submission. If you can't make this date, you can demo at any *earlier* date, but no later dates.

**Note:** The demo is **not optional**. If a project is not demonstrated, the grade will be at the discretion of the instructor.

## Grading

The project is worth a total of 600 points. Breakdown:

| Criterion | Points |
| --- |:---:|
| Functionality of application | 300 |
| Good use of [micro:bit](https://microbit.org/) capabilities | 100 |
| Input and output | 50 |
| Complexity of the application | 50 |
| Quality of demo | 50 |
| Clarity of report | 50 |

# Project Report

Fill out this template in place in the README of your own fork of the assignment repository. Put any supporting materials (diagrams, schematics, pictures, presentation slides, etc) in the [assets](assets) folder. You can reference them from this report. For example, [todo file](assets/todo.md). Use this [Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to format the report.

**Acknowledgement:** Adopted from [Bob Yusko](mailto:ryusko1@msudenver.edu).

## 1. Project Title

"Welcome to Crashy Bird"

## 2. Team

Joseluis Alamo Marquez Jr.
Samantha Gonzalez

## 3. Project Objective

We converted the Microbit game of Crashy Bird to Python and added a welcoming display and a score function that works with the B button input. 

## 4. Research

We used youtube source:

https://www.youtube.com/watch?v=MO-2DiHDZvg&t=1070s

## 5. Design
Input:
A button was used for flapping our bird
B button was used for showing the score
reset button used to rest the game


## 6. Development
Microbit Crashy Bird Game that was converted to Java, then converted to Python
Youtube sources

## 7. Testing

Flapping the bird kept leading to errors and we would keep downloading the game and tried multiple times. We kept changing our functions and erasing code, getting lost to the point we searched "How to not get out of the led screen, when making a microbit game". This then led us to youtube, which is where we found the function that works. After this we just personalized our own speed in pipes and bird flapping. 

## 8. Demo

The game worked perfectly in class. The flapping was too fast, so we took this in mind and decreased the speed in pipes from 0 to 2. 

## 9. Summary

We first started out the project with hopes to make something work with bluetooth. But, the microbit app didn't have a music option for ios. We were planning on using the input buttons a and b to change music from our playlist, but that is only possible with the android version of the app. So instead, we converted the Microbit game of Crashy Bird to Python and added a welcoming display and a score function that works with the B button input. The pipes themselves where created using the built in image function from microbit.org, with the same process as the RPSS game, except the leds are made lighter by being lighted by 5 instead of 9. We then had to control the speed of the pipes by putting them into a function, which is where we got into problems and the bird either got stuck or kept getting out of the led screen in our microbit. So, after multiple tries of downloading the game we headed to google to find out how to not crash the bird out of the game. This then led us to youtube, which is where we found the function that works. After this we just personalized our own speed in pipes and bird flapping. 
