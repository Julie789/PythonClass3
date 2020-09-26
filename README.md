# Practical Scripting with Python

## Importing from GitHub
- In the top left of Repl.it, select **+ new repl**
- Change tabs to select **Import From GitHub**
- Paste the following URL into the box:
  - ***github.com/Julie789/PythonClass3/***

### Using Time in Python
There are many packages that other people have made that we can use in our python program. To do this, we just need to import the package.
```
import time
```
This will give us access to the time related functions. Here are a few of the built-in time functions that we will use.
**time.sleep(secs)** - This will suspend execution for the given number of seconds.
**time.time()** - This will return the time in seconds.

## time.py
Create a program to show the time.

## Hangman.py  
Create a program to guess a word.
---

### Loops
If we want a program to repeat a task, we can setup a ***while*** loop. This loop will repeat as long as a given condition is True.
With any loop, there are 3 important steps.
- Create and initialize a variable.
- Create a loop condition
- Change the variable so the loop can eventually end.

#### Repeat n times
```
#initalize
count = 1

#test
while count < 10:
  print("Hello")
  #change
  count = count + 1

print("The loop is done")
```

#### Repeat until something happens
```
#initalize
play = "y"

#test
while play == "y":
  print("We are playing")
  #change
  play = input("Play again? (y/n): ")

print("Game over")
```

### Until next class
- How could time program make your life easier?
- What else could we do with time and looping?
