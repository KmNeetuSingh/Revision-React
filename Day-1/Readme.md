### OBSERVATIONS OF DAY-1:-
##  Declarative Programming :- 
 Declarative programming in which we are focusing  on describing what the desired outcomes should be rather than detailing the specific tasks to acheive it .Html is inherently decelarative , as it describes the structure of web pages without specifying the steps to render them. React is also a declarative type .

## Props:-
# Readability
# Maintainability
# Reduced Side Effect
## Cons :- 
# Less Control
# Learning Curve
# Performance

## Imperative Programming :-
Imperative programming in which we are focusing on to acheieve a desired  result by providing expilicity commands or statements. for example in javacscript dom manipulation .
## Props :-
# Fine -grained control
# Explicitness
# Flexibility
## Cons:-
# Complexcity
# More Boilerplate Code 
# Error -Prone 

Suppose two people want to attend the Ganpati Puja, and both decide to wear a kurta. 

1. The first person goes to the market, buys the fabric, gives it to the tailor, and provides step-by-step instructions on how they want the kurta made. Afterward, they get it pressed and ready for the event.
   
2. The second person simply orders a ready-made kurta online and has it delivered to their home.

Now, you can tell me react is which type of programming language , React lets you define the UI based on the current state, while React handles the DOM updates automatically, leading to cleaner and more maintainable code..

...In a simple term you can say that react is javascript libarary  for building dynammic user interfaces using reuseable components.......React allows to describe UI's on terms of state .....making ...code more readable...easier to debug.
### REACT AND REACT-DOM
React introduces a declarative approach to UI development, minimizing direct DOM interactions and improving performance and developer efficiency.

###

## Why React ?
React simplifies the creation of complex and interactive UI's by direct dom manipulation.
....direct dom manipulation is slow so react use virtual dom....making ui ..updates in more efficient way ...
## Virtual - DOM
It is a light weight copy of the actual DOM in the browser serving as a staging area for changes before they are rendered on the screen.
It's complete the process in three stages.....
# Update :-
Components changes..React..VirtualDOM.. (If are facing the issue with the components don't worry it is simple  like a function but its return jsx or html element we will further discuss it okay.. )
# Diffing :- 
React compares the updated VD with a pre -updated version to identify changes.
# Reconcilliation:-
It's an algorithm by the help of it's react updates the actual DOM with only the changes identified in the previous steps , rather than rendering the entire DOM.
 
### Hey what you think REACT is libaray or framework......
# In a strictly way ...
React is libarary because its focuses on the UI and does not enforce on application software.
# In a practically way .....
It can functions like a framework when used with additional tools to build full-featured applications.
So , we can say that React in its core functionality is libarary but it acn act liek a framework in the context of full development stack.


### JSX
JSX stands for javascript XML....SYNTAX extension for javascript that allows us to write the html like code with..Oin javascript files.Provides more intuitave and concise syntax for generating react Elements.It's capabilities  such as interplotation, self closing tags, event -handling, the spread operators, fragementsa and inline style .

Overall , We can say that its compiled into js by tool like babel before being rendered in the browser.


### Babel....A transpiler..
It's transform js code into older version of js (ES5) that is the compitable with the older version of the browser or enviroment ........