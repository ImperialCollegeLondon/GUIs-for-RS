# Graphical User Interfaces for Research Software

## Locations and Dates

- University of Glasgow - 14th-15th April 2020 - FREE REGISTRATION OPEN NOW!
- University of Nottingham - 1st-2nd July 2020
- Imperial College London - 23rd-24th September 2020

## Introduction

Research software has been a driving force behind the birth and rapid growth of informatics, but it was the appearance of graphical user interfaces (GUI) in the 1980s that made computers accessible to everyone. A GUI helps to reduce the learning curve for using software, increases the base of potential users and can ultimately increase citations and impact. Moreover, a well-designed GUI can perform validation and increase the robustness and reproducibility of the results, productively decoupling developers from users.

The goal of this workshop is to help researchers lose their fear - or reluctance - to invest time developing a GUI for their research software, and help them to give those first steps in the development of graphical user interfaces.

## Syllabus

### 1. GUI for research software: Why are they relevant?

Research software (RS) is designed to facilitate answering research questions, and it achieves this goal by running calculations, modeling some phenomena or managing and visualizing datasets, among many others. This is what RS is meant to accomplish, first and foremost, and everything that does not go in this direction is never a priority. GUIs in research software are nearly always considered as an aftermath - if considered at all! -, and add-on usually not very sophisticated to try to make the software more accessible. And the result is rarely fit for purpose. In this first lecture of the course we will try to answer the question of when research software might benefit from a GUI, when it will not, and what the benefits that having a well design GUI can bring to the table.

### 2. Introduction to interface design

**Guest lecture by**: [Mark Turner](INSTRUCTORS.md#mark-turner)

As RSEs we’re always writing code, testing code and writing documentation about that code. However, every so often we have to build something that has a user interface. All of a sudden you’re not just a programmer and a database engineer but a UI/UX designer too. For those who find the world of UI/UX design a little challenging, this talk will introduce simple core concepts that form the basis of a well-designed, useful, maybe even aesthetically pleasing user interfaces. These concepts are transferable across programming languages, the web and even onto printed materials and slide decks. Hopefully by picking up a few tips of what to do, and what not to do, everyone’s user interfaces will be a little easier to use, and maybe even a little better to look at.

### 3. GUI Architectural patterns

"[An architectural pattern is a general, reusable solution to a commonly occurring problem in software architecture within a given context.](https://en.wikipedia.org/wiki/Architectural_pattern)" The context, in our case, is graphical user interfaces and the commonly occurring problem is how to keep a separation of concerns between the business logic and the visual, interacting elements, as well as how they communicate with each other. In this lecture we provide an overview of some of the most common patterns in GUI Architectures, such as the model-view-controller, highlighting some of their advantages and disadvantages... as well as when to manage without a pattern altogether!

### 4. GUI toolkits

So far, we have been discussing general GUI theory, broadly applicable to any programming language and GUI toolkit. The fact is that the choice of language - and once this is chosen, the specific GUI toolkit to use - will have an strong impact on the implementation of the architectural patterns and the flexibility in UI/UX design. It might even condition altogether what you can and cannot do! In this lecture we will give and overview of some common GUI toolkits for Python, suitable for desktop, mobile and web applications, discussing their pros and cons.

**Note**: Despite the examples being focussed on Python, many of these GUI toolkits are available with similar API and functionality in other programming languages. As a result, non-Python users will still benefit from the contents of this lecture.

### 5. Testing GUIs

Testing your code and, ideally, implementing a CI/CD system is a must in any software project. And GUIs are no exception. But being GUIs dependent on displaying some graphics and having a user interacting with the different elements makes this automatic testing slightly more challenging. In this final lecture of the course we will give some guidelines on how this testing can be accomplish, what aspects of the GUI should be check and which ones should rely on the GUI toolkit developers having done a good testing job on their side.

### 6. Hackday!

TO BE COMPLETED

## Acknowledgements

The development and delivery of this course has only been possible thanks to the support of the Software Sustainability Institute Fellowship programme 2020.

I would also like to thank Frances Cooper (University of Glasgow) and Louise Brown (University of Nottingham) for their invaluable support as local organizers, arranging the venue and helping me with all the in-situ arrangements.