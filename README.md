# Monte-Carlo-Model
Team E7 of Finsearch

We aim to demonstrate monte carlo model for option pricing via our code written in python.
It involves two examples one being related to option pricing model and other one in which we demonstrate general use of monte carlo model by solving an integral.


For second problem, Our algorithm looks like this:

1. Get a random input value from the integration range
2. Evaluate the integrand
3. Repeat Steps 1 and 2 for as long as we want
4. Determine the average of all these samples and multiply by the range
