LearningScalaMaterials
======================

Supplementary materials for [Learning Scala] (http://shop.oreilly.com/product/0636920030287.do), O'Reilly Media, 2014.


## Answers to Exercises 

Answers to exercises in the first four chapters are now available. The answers for the exercises in the rest of the chapter will be available by the end of December 2014.

* [Chapter 1 - Getting Started] (https://github.com/swartzrock/LearningScalaMaterials/blob/master/Exercises/Ch1-GettingStarted/exercises.asc)

* [Chapter 2 - Working With Data] (https://github.com/swartzrock/LearningScalaMaterials/blob/master/Exercises/Ch2-WorkingWithData/exercises.asc)

* [Chapter 3 - Expressions and Conditionals] (https://github.com/swartzrock/LearningScalaMaterials/blob/master/Exercises/Ch3-ExpressionsAndConditionals/exercises.asc)

* [Chapter 4 - Functions] (https://github.com/swartzrock/LearningScalaMaterials/blob/master/Exercises/Ch4-Functions/exercises.asc)



## Errata

Here are some of the known errors in the first edition of [Learning Scala] (http://shop.oreilly.com/product/0636920030287.do). Thank you to all of the readers who have reported them!

### Chapter 1 - Getting Started

#### Exercises

5) Another way to load external Scala code is to paste it into the repl in "raw" mode, where the code is compiled as if it were actually in a proper source file. To do this, type ":paste -raw", hit return, and then paste the contents of your source file from exercise 4. After exiting "paste" mode you should see the greeting.

-------------------------------------------------------------------------------
The "raw" mode here is a mistake. Please use ":paste", not ":paste -raw". 
-------------------------------------------------------------------------------

### Chapter 3 - Expressions and Conditionals

#### Exercises

6) Can you rewrite the answer to question 6 to fit on one line? It probably won't be easier to read, but reducing code to its shortest form is an art, and a good exercise to learn the language.

-------------------------------------------------------------------------------
That should be "question 5", not "question 6". Unless you would like a head start on thinking recursively, please assume that the previous question, number 5, is the one to rewrite.
-------------------------------------------------------------------------------



## Copyright and license

Code and materials copyright 2014-2015 Jason Swartz. Released under the [the MIT license] (LICENSE) .
