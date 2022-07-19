# Study Guide for Quiz 1(Jul 21st)


Primary resources (desceding order by **importance**)

  * **Lecture notes** with emphasis on
      * How do we define each concept?
      * **Practice questions** -- reasoning for every options(why correct? why wrong?)
   
  * **R Session code** with emphasis on
      * Why are we running this code? What do we want to check by running the code?
      * What does specific code mean? Which element is needed for running a sepcific function?
     
  * **Recommended exercises** in [OS](https://www.openintro.org/book/os/)
      * Emphasis on how the related concepts can be used in real-life example

  * [**Sample quiz**](notes/Quiz1-sample.pdf)
      * Thoroughly review lecture notes, R code and practice questions from the textbook prior to working on the sample quiz
      

## Chapter 1. Introduction to data
### Learning Objective
 * Variable Types: Numerical vs. Categorical/ Response vs. Explanatory/ Obervational vs. Experimental
 * Sampling method: Simple random sampling, Cluster sampling, Stratified sampling
 * Causation vs. Correlation/Association




### Resource 

<details>
 
#### [Lecture note](notes/Lec02.pdf)
#### Exercises
 * (p.11) Exercise 1.2: Sinusitis and antibiotics
 * (p.19) Exercise 1.5: Cheaters, study components
 * (p.20) Exercise 1.8: Sinusitis and antibiotics Part II
 * (p.31) Exercise 1.27: Sampling strategies
 * (p.35) Exercise 1.30: Vitamin Supplements
 * (p.36) Exercise 1.37: Chia seeds and weight loss
 * (p.37) Exercise 1.39: Flawed reasoning
 * (p.37) Exercise 1.41: Eat better, feel better

#### R Session
 * How do we use the following packages: `tidyverse`, `ggplot2`?
 * \[`arbuthnot`\]Interpret the trend on the number of new born boys/girls.
 
</details>

## Chapter 2. Summarizing the data

### Learning Objective
 * Numerical Data
   * Graphical Summary: Histogram, Boxplot, Scatterplot
   * Numerical Summary: Mean and Variance
 * Categorical Data: Frequnecy table, Contingency table, Barplot, Mosaic plot
 * Overview for Hypothesis Testing(Malaria vaccine)

### Resource
#### [Lecture note](notes/Lec04.pdf)
 * Special emphasis on the **simulation** for malaria vaccine
 * **Sec 2.3. Case study: malaria vaccine**

#### Exercises
 * (p.56) Exercise 2.2: Associations
 * (p.56) Exercise 2.5: Parameters and statistics
 * (p.57) Exercise 2.10: Mix-and-match
 * (p.58) Exercise 2.12: Median vs. Mean
 * (p.70) Exercise 2.24: Raise taxes
 * (p.76) Exercise 2.26: Heart transplants
 * (p.77) Exercise 2.31: Oscar winners
 * (p.78) Exercise 2.34: Marathon winners

#### [R Session](notes/Lec05.pdf)
 * The important part is 
    * why this particular graph is useful in summarizing the data
    * how to interpret the graph

## Chapter 3. Proabibility

### Learning Objective
 * Definition of Probability: Frequentist vs. Bayesian
 * Law of Large Numbers
 * Independent vs. Disjoint vs. Complementary
 * Product rule for independent Events: P(A \cap B) = P(A) \times P(B)
 * General addition rule: P(A \cap B) = P(A) + P(B) - P(A \cap B)
 * Sampling with, without replacement

### Resource
#### [Lecture note](notes/Lec06.pdf)

#### Exercises
 * (p.92) Exercise 3.1: Ture or false
 * (p.92) Exercise 3.5: Coin flips
 * (p.93) Exercise 3.9: Disjoint vs. independent
 * (p.109) Exercise 3.13 (a), (b)-i, (b)-ii, (c)
 * (p.114) Exercise 3.23: Marbles in an urn
 * (p.114) Exercise 3.27: Student outfits
 * (p.124) Exercise 3.29: College smokers
 * (p.124) Exercise 3.31: Heart win
 * (p.129) Exercise 3.40: Health coverage, frequencies
 * (p.130) Exercise 3.44: Scooping Ice cream
 
#### [R Session](notes/Lec07.pdf)
 * Special emphasis on **Law of Large Numbers** simulation

## Chapter 4. Distributions of Random Variables

### Learning Objective
 * Normal Distribution
    * Parameters: \mu(mean), \sigma(standard deviation)
    * Calculate the probability using `pnorm`
    * Calculate the percentile using `qnorm`
    * Z-score and standard normal distribution
 * Bernoulli Distribution: Milgram experiment
 * Binomial Distribution
    * Parameters: n(the number of trials), p(probability of success)
    * Normal approximation to binomial distribution
 * Poisson Distribution
 
### Resource
#### [Lecture note](notes/Lec08.pdf)
 * Sec 4.5. Poisson distribution -- to see the examples potentially following poisson distribution

#### Exercises
 * (p.142) Exercise 4.3: GRE scores, Part I -- use `pnorm` to calculate the probability
 * (p.142) Exercise 4.5: GRE scores, Part II -- use `qnorm` to calculate the percentile
 * (p.148) Exercise 4.11: Is it Bernoulli?
 * (p.148) Exercise 4.12: With and without replacement
 * (p.157) Exercise 4.22: Arachnophobia
 * (p.166) Exercise 4.27: University admissions
 * (p.166) Exercise 4.39: Auto insurance premiums
 
#### [R Session](notes/Lec09.pdf)
 * Emphasis on the usage of `pnorm`
 
