# Hangman game

> The popular word-guessing execution game, made for the WBS Coding School "Data Science" bootcamp

---

> created **January 23rd-24th 2023** 
>
> by **Therese Andrä** 
>
> as first project during the Data Analysis Bootcamp of WBS Coding School
>
> coded in ```Python```

---
### Description and Rules

Hangman is a guessing game where the player(s) try to guess the word by suggesting a letters.  
Player is allowed a certain number of mistakes.  

The game starts with a word where all letters are replaced with a `-` so the only information available to a player is a number of letters in a word.  
**Start**: `------`  

For each correctly guessed letter, a position of the letter is revealed (if there are multiple positions for a same letter, they are all revealed.  
**Correct**: `-E--E-`  

For each wrongly guessed letter, number of allowed mistakes decreases by 1.  
**Wrong**: 'Number of allowed mistakes is now 5'

Name of the game comes from a drawing of a hanged stick figure. For every mistake a new element of a hanged figure is added.  
If a player guesses a word before the last element of a figure is added, a player wins.  
If a player doesn't guess a word before the last element of a figure is added, player loses.

### **Here you can see a simulation of 3 different steps:**  

Hidden word is: ------  

==============================================================  

Pick a letter:  

 S  
 
Correct! There is a letter S in a secret word!  

S-----  

==============================================================  

Pick a letter:  

 V  
 
WRONG! Number of mistakes left: 5  
  
        ____________  
         |  
         O  
==============================================================  
Pick a letter:  
 L  
WRONG! Number of mistakes left: 4  
  
        ____________  
         |  
         O  
        /  
==============================================================  
Pick a letter:  


