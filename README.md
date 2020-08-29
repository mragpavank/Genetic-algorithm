# Genetic-algorithm

Problem Statement: 
Let’s say we have selected N financial assets we want to invest in. They can be stock, funds, bonds, ETF etc. Each one of them has many historical returns, that is the price relative difference from one period to another. Periods can be days, weeks, months and so on. 
Build an investment portfolio with a  mix of many assets (They can be stock, funds, bonds, ETF) together allocating a fraction x of total  capital to each one of them. Each fraction is called weight.  The goal of portfolio optimization is to find the values of the weights that maximize some performance metric( in this case Returns)  of our portfolio under some constraints. 
Data:  csv files with returns from different organizations // need to update
About Data:  Historical returns from different organizations. // need to update
Tasks: 
Perform the following activities :
1.	Read the data 
a.	Calculate the historical returns say( 3,6,12,24,36 in months) for each stick given

2.	Define  chromosome i.e initial weights  for each stock
3.	Define the following functions
a.	population - A set of randomly generated chromosomes
b.	fitness_function-  Check the generated chromosome is fit or not based on a condition.Think of the condition which tests whether the chromosome is fit or not.
c.	seletion_population - It filters the elite chromosomes which have highest returns.
d.	evaluation_function-  A function which does mutation,mating or crossover based on a probability and builds a new generation of chromosomes.

4.	Iterate the process calling  evaluation function and selection function until you get a feasible solution until there is no change in maximum returns or you reach the maximum number of iterations.

References:
1.	https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4923467/
2.	https://research.ijcaonline.org/volume117/number1/pxc3902315.pdf
3.	https://www.researchgate.net/publication/268037272_A_Hybrid_Portfolio_Asset_Selection_Strategy_Using_Genetic_Algorithms_GA
