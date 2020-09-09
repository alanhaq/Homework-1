#Business Analytics HW1
#Alan Huang


#Coding in R

#Problem 1
#The following command generates a vector of 1000 random numbers
#ranging from the values -10 -> 10
vector_of_random_numbers = runif(n=1000, min =-10, max=10)
random_numbers_mean      = mean(vector_of_random_numbers)

#Problem 2
#Code a script that takes one input from the user (name and age) and displays the values.
name = readline(prompt="Enter your name: ")
age  = readline(prompt="Enter your age: ")
print(paste("Your name is ", name, "and your age is ", age))

#Problem 3
#Write a script where the user enters a path and the computer changes the working directory.
path_to_go = readline(prompt="Enter a path: ")
setwd(path_to_go)

#Problem 4
#ls() command tells you what variables are in your working environment
ls()

#Problem 5
#Vector of numbers between 1-150
vector_of_150       = 1:150
vector_of_150_mean  = mean(vector_of_150)
mean_divisable_by_3 = mean(vector_of_150[vector_of_150%%3 == 0])

#Problem 6
#Vector which contains 10 random integer values between -50 and +50
vector_of_10_ints         = round(runif(n=10, min =-50, max =50))
vector_of_10_ints_sum     = sum(vector_of_10_ints)
vector_of_10_ints_mean    = mean(vector_of_10_ints)
vector_of_10_ints_product = prod(vector_of_10_ints)

#Problem 7
#Program that asks the user to introduce 3 integers numbers. Call them initial, final, 
#and denom. The program tells the user the sum, the average and the product of all the 
#numbers from initial to final that are divisible from denom.
initial = readline(prompt="Enter 1st integer: ")
final   = readline(prompt="Enter 2nd integer: ")
denom   = as.integer(readline(prompt="Enter 3rd integer: "))
#Vector given user input
vector_initial_to_final = initial:final
#Vector of initial to final numbers divisible by denom
vector_divisible_by_denom = vector_initial_to_final[vector_initial_to_final%%denom == 0]
#Display sum, average, and product of numbers divisible by denom
print(paste("The sum of numbers between ", initial, " and ", final, 
            " divisable by ", denom, " is ", sum(vector_divisible_by_denom)))
print(paste("The average of numbers between ", initial, " and ", final, 
            " divisable by ", denom, " is ", mean(vector_divisible_by_denom)))
print(paste("The product of numbers between ", initial, " and ", final, 
            " divisable by ", denom, " is ", prod(vector_divisible_by_denom)))


#Math With R

#Problem 1
#Script where the user is prompted for a number and R computes its square root.
#Taking the sqrt of -1 give a NaNs error since it cannot be done
x_sqrt = sqrt(as.integer(readline(prompt="Enter an number: ")))

#Problem 2
#Function where the user is prompted for a number and R computes its exponential.
x_exp = exp(as.integer(readline(prompt="Enter an number: ")))

#Problem 3
#Function where the user introduces a number and R computes its natural logarithm.
x_log = log(as.integer(readline(prompt="Enter an number: ")))


#Calculus Questions

#Problem 1
#Suppose that a function is always increasing, (like for example F(x) = exp(x)). 
#We can assure with probability one that its derivative must be non-negative. 
#Is this true or false?
#True. By definition if a function is increasing, its derivative is positive.

#Problem 2
#Find the domain of the functions:
#F(x) = sqrt(x+1), Domain is [-1,Inf]
#F(x) = sqrt(exp(x+1)), Domain is [-Inf,Inf]

