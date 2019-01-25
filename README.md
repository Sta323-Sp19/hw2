Sta 323 - Homework 2
-------------

Due by 11:59 pm on Thursday 1/31/2019.


<br/>

![fizz buzz](fizzbuzz.png?raw=true)

<br/>

## Task 0 - Watch "Code Smells and Feels" by Jenny Bryan

At this year's UseR conference, Jenny Bryan gave a keynote lecture titled "Code Smells and Feels", a video of this lecture is available on [youtube](https://www.youtube.com/watch?v=7oyiPBjLAWY) and a repo containing the slides and related materials is on [github](https://github.com/jennybc/code-smells-and-feels).

This talk is a wonderful introduction into what good R code should look like as well as the process of refactoring existing code to improve its overall quality. I strongly recommend that you take an hour to watch the lecture in its entirety. At the very least her slides are also worth skimming through.

<br/>

## Task 1 - Re-Implement FizzBuzz 

For this homework you have been assigned to a group that includes 2 or 3 other students from the class, these groups were constructed randomly and will change for each subsequent assignment. Your initial repo master branch contains similar files to the hw1, however this repo also contains additional branches named after each team member which contains all contents of your hw1 repository.

Your tasks for this assignment is to combine all of your implementations together into a single clean / elegant / readable implementation of `fizzbuzz`. You should take advantage of the additional material we have covered as well as some of the suggestions Jenny made in her talk to improve and streamline your implementation.

In particular, you implementation must now implement fizzbuzz using R's S3 object system. In other words, your `fizzbuzz` function must now be implemented as

```r
fizzbuzz = function(v) {
  UseMethod("fizzbuzz")
}
```

and you and your team should now implement the additional functions necessary to make this work.


<br/>

## Task 2 - FizzBuzz validation

Combine all of your collective test cases and validate that your new implementation produces the expected results across a wide variety of inputs.

<br/><br/>

## Submission and Grading

This homework is due by *11:59 pm Thursday, January 31st*. You are to complete the assignment as a group and to keep everything (code, write ups, etc.) in your team's repository (commit early and often). Only the work commited to the repositories **master** branch will be graded at the deadline.

The final product for this assignment should be a single Rmd document (`hw2.Rmd`) that contains all code and text for the tasks described above. This document should be clearly and cleanly formated and present all of your results. Style and formating does count for this assignment, so please take the time to make sure everything looks good and your text and code are properly formated. This document must be reproducible and I must be able to compile it with minimal intervention - documents that do not compile will be given a 0. 

As with the first assignment we will not be enforcing any particular coding style, however it is important that the code you team produces is *readable* and *consistent* in its formating. There are several R style guides online, e.g. from [Google](https://google.github.io/styleguide/Rguide.xml) and from [Hadley Wickham](http://r-pkgs.had.co.nz/style.html). As a group you should decide on what conventions you will use and the entire team should conform to them as much as possible.

<br/>
