# 



## Basic Programming (C#)

Idea  is to get a basic grasp of programming because this will help a lot with understanding and syntax.
The goal is to be able to create small programs in terminal, solve mathematical problems and implement basic
features in Unity. 

We begin with super basic stuff and ramp upp quickly, meaning we start with stuff you likely already know.
Try not to breeze through these too quick, it is always good to repeat basics, do the task even its repetitive!

The tasks below will serve as a backbone to track how much you've learned, they are not really in the best order,
some easier are toward the beginning but scroll through them from time to time and when you feel ready to try one. 
These are not meant to be solved with little to none googling or outside help, they are for your eyes only. 

One thing that id like to stress, learning programming is quite heavy in the beginning, 
most of the time you will feel like you are understanding anything and are just struggling, the tasks are meant 
to prevent this a bit by giving you a metric on your progress. These are not gonna be the only metric a long the "course", and 
all of these are meant to be completed without tutorials or chatGPT, you are only allowed to google very specific things.

Learning programming for most is a lot of trying a failing, the more you fuck around the more you learn.

Most of the things are meant to be done within the IDE (Rider for example) unless otherwise explain, meaning if there is an outside
source of knowledge, redo everything within your editor, practice and being getting conftable is important. 

[Practice tasks part 1](https://github.com/Litene/Programming-Education/blob/main/O_vningsuppgifter%2C%20del%201.pdf)

[Practice tasks part 2](https://github.com/Litene/Programming-Education/blob/main/O_vningsuppgifter%2C%20del%202.pdf)

The final part of the programming part is to do a game jam with friends as a programmer!

Some things are very simplified for learning purposes, example: 
You always place brackets after doing X, this statement is likely true for almost all cases, but its better to learning
the rules then learning the exceptions. 

```csharp
namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");    
    }
  }
}
```

### Part 0 Setup
#### Installing the IDE
There are many choices for IDE (Integrated Development Environment), Jetbrains Rider is arguably the best one, and is not free for personal use.
Rider provides something called Syntax highlighting/intellisense for HLSL (which makes programming a lot easier), compiles faster (fast load times)
and better suggestions compared to its competitors.

Go through the installation normally and click in add file associations, 

#### Setting it up perfectly for you
I'll give a few tips which I feel is useful and makes it easier to code. 

### TIPS INCOMING

#### 

### Part 1 The Basic Basics

Every part of this little course will come with 10 exercises.
The last one being a little bigger where you are encourages to experiment.

The education is a good mix of different sources and my own opinions, for the first section W3Schools

Where you will do all the basics as listed here: [W3Schools Tutorial](https://github.com/Litene/Programming-Education/blob/main/W3.png)

[W3Schools Link](https://www.w3schools.com/cs/index.php)

### Exercise 1 Nim

The goal is to create the game NIM that plays against a computer

Rules for the game can be found at [Wikipedia](https://sv.wikipedia.org/wiki/Nim)

The computer should pick a random amount of sticks between 1 and how many the rules allow.
The `Random` class allows to get random int between a predetermined range.

Access it by making an instance of the class through

Random YourName = new Random();

int YourRandomNumber = YourName.Next(MinValue, MaxValue);

Where you give the lowest value and the maximum value.

The Game Loop is a common thing, the easiest way to achieve it is through a while loop with a bool ``bool Game Over = false``
for example. And if someone wins/looses is set to true.

There are countless solutions/ways to program this. 

#### Part 1

* The game should end when either the computer or player wins.

#### Part 2

A big part of programming is refactoring, it essentially means redoing/reworking how the code looks.

This helps a lot with code readability, and modularity when done right. 

The assignment is therefore to refactor based the criteria below, these are difficult to please seek advice guidence if needed.

* Main Should only have one method call ergo ``MyGame.StartGame()`` Rest of the game should be in a different class.
* Every functionality should have its own method ``CheckIfGameOver()`` For Example

#### Part 3

This is the cleanup part where its time to wrap it up and add some security.

There a complete game has to account for user error and also being able to play again therefore the requirements are:

* Give the player the option to restart the game when its game over
* Add the option to play either vs a computer or another playing (where they take turns to give input)
* No Incorrect Input

#### Part 4

Nim is a beat game, there is a tactic so you can't loose therefore you should make it so that the computer can't loose.

#### Other

After you made it through the basics of W3School and Excercise, do Assignment 1,2,4,7,9 in tasks part 1.

### Part 2 

### Part 3

## HLSL

## Render Programming

## Sources

https://minionsart.github.io/tutorials/?type=built-in

https://catlikecoding.com/unity/tutorials/

https://youtu.be/C8YtdC8mxTU?si=1GqAFiuHlKzXYCE-

https://www.youtube.com/watch?v=BFld4EBO2RE

https://iquilezles.org/

https://www.youtube.com/watch?v=fjOdtSu4Lm4&list=PLImQaTpSAdsArRFFj8bIfqMk2X7Vlf3XF

https://www.youtube.com/watch?v=kfM-yu0iQBk&list=PLImQaTpSAdsCnJon-Eir92SZMl7tPBS4Z

https://www.youtube.com/watch?v=YJB1QnEmlTs

https://www.youtube.com/watch?v=ml-5OGZC7vE

https://www.youtube.com/watch?v=CHYxjpYep_M