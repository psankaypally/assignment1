# assignment1
problem statement 
1. Please mention true or false for the below statements: 
a) Prescriptive Analytics is used to predict the future outcomes FALSE
b) Base R packages are installed automatically FALSE
2. What is Recycling of elements in a vector?
Answer is When applying an operation to two vectors that requires them to be the same length, R automatically recycles, or repeats, elements of the shorter one, until it is long enough to match the longer Vector.
3. Give an example of recycling of elements.
## Not run: 
# # z is the longest argument, with 6 elements
# recycle(x = 1:4, y = list(a = month.abb, b = pi), z = matrix(1:6, nrow = 3))
# ## End(Not run)
