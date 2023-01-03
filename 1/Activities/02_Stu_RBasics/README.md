# Student Homeroom

In this activity, you will play the role of a high school homeroom teacher. It’s the first day of school, and you want to use R to automatically create daily attendance sheets and locker combinations

## Instructions

This activity is broken into three parts. Also, keep the following in mind as you do this activity:

* To create a new R script file, go to File, select New File, and then select R Script.

* You may also work with an R Markdown (`Rmd`) file. To insert a code block, or chunk, in an R Markdown file, go to Code, then select Insert Chunk.

* To run a code chunk, press the green play button at the top right of a code chunk.

* Read [the documentation](https://rmarkdown.rstudio.com/lesson-1.html) for more information on R Markdown files.

### Part 1

* Create a vector of the following students:

  * Abraham
  * Beatrice
  * Cory
  * Dinah
  * Eric
  * Felicia

* Using the vector, create a function that will print daily attendance sheets, with today's date printed at the top. Then use a `for` loop to print each student's name.

* You will need to research how to create a function. To print the date in R, try `Sys.Date()`.

### Part 2

* Each student will be assigned a locker, and as their teacher, you are responsible for resetting the lock combinations. Create a function that will randomly generate a combination for each student. The combination should be three numbers, each ranging from 1 through 33.

* To generate (pseudo) random numbers in R, try `sample(33,3)`.

### Part 3

* Massive security breach! A hacker has accessed the combinations for any student whose first name’s second letter is `e`. Print the name of each of these students and a randomly generated combination of three numbers between 34 through 66.

  * **Hint:** You will have to research how to access a single letter in a string.

- - -

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
