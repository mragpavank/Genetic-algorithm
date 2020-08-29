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

Objective
Understand the usage of optimization techniques in real world scenarios and maximize returns from portfolio of stocks by allocating certain percentage of amount  using Genetic algorithm  taught as part of the module CSE7221o to solve the near real time use case from Financial Mathematics Domain.
Real-world Scenarios

1.	Portfolio Optimization
Portfolio optimization is the process of selecting the best portfolio (asset distribution), out of the set of all portfolios being considered, according to some objective. The objective typically maximizes factors such as expected return, and minimizes costs like financial risk. 
   	Using a Genetic Algorithm (GA), an artificial intelligence technique used to  build interactive dynamic portfolio selection strategy that will generate an optimal investment mix of assets based on user selection by maximizing the return of the Sharpe Ratio, a measure of the excess return received on a portfolio for the increase of volatility by acquiring a riskier asset.
    
2.	Feature Selection
Feature selection is a process that reduces the number of attributes and selects a subset of original features. Feature selection is often used in data pre-processing to identify relevant features that are often unknown previously and removes irrelevant or redundant features which do not have significance in classification tasks. Feature selection aims to improve the classification accuracy. The Genetic Algorithm is used to determine which features are the most predictive by defining chromosomes and fitness functions intelligently.

3. Bioinformatics  

 The Bioinformatics (BI) is a sequence alignment, usually three sequences which can be RNA, DNA and proteins. Because the three or more given sequences can be of large lengths, aligning them by hand can be time consuming and in some cases traditionally impossible. Thus BI comes into use thereby aligning each sequence, and revealing the similar part of the given gene. BI finds great use in bioinformatics where it is used to predict the protein structure, its function, family or its domain. These problems are related to AI and can be classified in the NP complete domain of problems. Thus with the goal of identifying maximum similarities among the sequences, we can use various approaches and techniques like Genetic Algorithms (GA) and its variants in BI.
There are many applications of GA in Bio informatic such as Multiple Sequence Alignment, Gene Prediction, and Population Genetics Modeling and DNS sequence matching.

Domain:  Financial  Mathematics
Background : 
Portfolio optimization is one of the most interesting fields of study of financial mathematics. Since the birth of Modern Portfolio Theory (MPT) by Harry Markowitz, many scientists have studied a lot of analytical and numerical methods to build the best investment portfolio according to a defined set of assets. The power of genetic algorithms makes it possible to find the optimal portfolio





References:
1.	https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4923467/
2.	https://research.ijcaonline.org/volume117/number1/pxc3902315.pdf
3.	https://www.researchgate.net/publication/268037272_A_Hybrid_Portfolio_Asset_Selection_Strategy_Using_Genetic_Algorithms_GA
