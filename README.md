# Intro to R

### Coding in R
1. Run the following command:
   ```
   vector_of_random_numbers = runif(n=1000, min =-10, max=10)
   ```
   a. What does the output do?

   b. Compute the mean of `vector_of_random_numbers`.

1. Code a script that takes one input from the user (name and age) and displays the values.
   ```
   Enter your name: Xavi
   Enter your age : 18
   "Your name is Xavi and your age is 18"
   ```

1. Write a script where the user enters a path and the computer changes the working directory.

1. One thing that you will have to do when you are a coder is learning how to google and understand documentation.

   For example, can you find online the command that tells you what are the variables are in your working environment?

1. Create a vector of numbers from 0 to 150.

   a. Compute its mean.

   b. Compute the mean but only for the numbers contained in that sequence that can be divided by 3.

1. Create a vector which contains 10 random integer values between -50 and +50.

   a. Write an R script that computes its sum, mean and product.

1. Write an R program that asks the user to introduce 3 integers numbers. Call them `initial`, `final`, and `denom`. The program tells the user the sum, the average and the product of all the numbers from `initial` to `final` that are divisible from `denom`.

  > Hint: Use `x%%y==0` to check if a number `x` is divisible by `y`.

### Math with R

1. Write a script where the user is prompted for a number and the R computes its square root.

   a. Can you compute the square root of -1? Why or why not?

1. Write a function where the user is prompted for a number and the R computes its exponential.

1. Write a function where the user introduces a number and the R computes its natural logarithm.

### Calculus Questions
1. Suppose that a function is always increasing, (like for example F(x) = exp(x)). We can assure with probability one that its derivative must be non-negative. Is this true or false?

1. Find the domain of the functions:

   a. `F(x) = sqrt(x+1)`

   b. `F(x) = sqrt(exp(x+1))`
