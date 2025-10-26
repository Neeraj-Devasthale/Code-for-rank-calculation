## Dominance hierarchies:

Dominance hierarchies are found in many species, across a spectrum of natural and laboratory environments. A method to quantify dominance scores and individual ranks based on win-loss data was proposed by H. A. David in 198714. This metric is called as David’s score. 

We also measure ranks using another system called as Elo system. In this system, all the animals are assumed to have a same score and this score is then updated after accounting for every interaction. However, this method is highly sensitive to order of interactions. Hence, to account for this, we randomly permuted the events 1000 times and average Elo score of the bird was taken as the final score16. Higher score indicates higher rank. 


The mathematical details of these are included in Dominance rank calculation explaination.docx file. The code implemets these mathematical formulations for calculating scores.

### Input to the code- A network in the form of adjacency matrix
### Output- Dominance scores and ranks in an excel file
