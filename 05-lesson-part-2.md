# Lesson: Part II

*Let's keep doing some coding!* These examples are a bit tricker than the ones you just saw.  

# Save your work in R objects

In R, we don’t just do calculations and look at the results on the R console. We usually save the results of the calculations somewhere we can find them later.

Pretty much anything, including the results of any R function, can be saved in an R object. This is accomplished by using an assignment operator, which looks kind of like an arrow `<-`.

Here’s a simple example to show how it’s done. Let’s make up a name for an R object; we will call it `my_fav_num`. Then let’s think of what our favorite number is (say, 20), and save it in the R object. Go ahead and run the code below to see how this works.

<iframe frameborder="0" height="400" scrolling="no" src="https://uclatall.github.io/mtucker-coding-study/data-camp/dcl-example-05.html" style="border: 0px #ffffff none;" width="90%"></iframe>


# Vectors

We’ve used R objects so far to store a single value. But an R object can also store a whole set of values, called a vector. You can think of a vector as a list of values.

The R function  `c()`  can be used to combine a list of individual values into a vector. You could think of the “c” as standing for “combine.” Run to code below to see how it works.  

<iframe frameborder="0" height="400" scrolling="no" src="https://uclatall.github.io/mtucker-coding-study/data-camp/dcl-example-06.html" style="border: 0px #ffffff none;" width="90%"></iframe>

As you can see from the example above, vectors can store different types of values.

## Numerical Values

If R knows that you are using numbers, it can do lots of things with them. We have seen, for example, that R can perform arithmetic operations on numbers: addition, subtraction, multiplication, and division.


## Character Values

Characters are comprised of text, such as words or sentences. (Numbers can also be treated as characters, depending on the context. For example, when 20 is in quotation marks like this – “20” – it will be treated as a character value, even though it includes a number.) Character values are in between quotation marks, " “.

## Boolean Values

Boolean values are either TRUE or FALSE. Maybe we have a question such as: Is the first element in the vector `my.vector2` “a”? We can ask R to find out and return the answer TRUE or FALSE. We can do that by using the comparison operator `==` (it just means equal). Run the code below to see how it works.

<iframe frameborder="0" height="400" scrolling="no" src="https://uclatall.github.io/mtucker-coding-study/data-camp/dcl-example-07.html" style="border: 0px #ffffff none;" width="90%"></iframe>

In the code above, we used brackets with a number in it to select a single element in a vector. In the code above, we selected of the first position in `my.vector2` by writing  my.vector2[1]. We then used the comparison operator `==` to see if that element is equal to "a".

Most of the questions we ask R to answer with a TRUE or FALSE involve comparison operators such as `>`, `<`, `>=`, `<=`, and `==`. The double `==` sign checks if two values are equal. There is even a comparison operator to check whether values are not equal: `!=`. For example, 5 `!=` 3 is a TRUE statement.


*Great job coding!* Now, let's practice what you've learned.

# Practice Question 3

<iframe frameborder="0" height="400" scrolling="no" src="https://uclatall.github.io/mtucker-coding-study/data-camp/dcl-practice-03.html" style="border: 0px #ffffff none;" width="90%"></iframe>


# Practice Question 4

<iframe frameborder="0" height="400" scrolling="no" src="https://uclatall.github.io/mtucker-coding-study/data-camp/dcl-practice-04.html" style="border: 0px #ffffff none;" width="90%"></iframe>
