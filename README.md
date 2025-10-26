Dominance hierarchies:
Dominance hierarchies are found in many species, across a spectrum of natural and laboratory environments11-13. A method to quantify dominance scores and individual ranks based on win-loss data was proposed by H. A. David in 198714. This metric is called as David’s score. First, a probability matrix is computed such that 
Pij (probability of i winning over j)=Mij/(Mij+Mji)
We then compute an animal’s weighted wins and losses as follows:
Weighted wins vector for animal i= Wi=∑_(n=1)^j▒Pin  
Weighted losses vector for animal i= Li=∑_(n=1)^i▒Pnj
These are then arranged to form n x 1 vectors W and L where ith term in the vector is Wi and Li respectively. A second order term is now computed as follows
W2=PW
L2=PL
These second order terms are important since they allow us to also consider the performance of other animals and their relative strength. In the final score computation, we consider both 1st order term (an indicator of direct win-loss dynamic) and these 2nd order terms. David’s score is finally given by- 
David^' score for animal i=Di=(Wi+W2i)-(Li+L2i)

We also measured ranks using another system called as Elo system. In this system, all the animals are assumed to have a same score and this score is then updated after accounting for every interaction. However, this method is highly sensitive to order of interactions. Hence, to account for this, we randomly permuted the events 1000 times and average Elo score of the bird was taken as the final score16. Higher score indicates higher rank. After a win-loss interaction, the win probability is calculated as:
P=1/(1+10ˆ[Score(l)-Score(w)/400] )

The Elo scores are then updated as follows:
Score(w)(new)= Score(w)(old)+ k*(1-P)
Score(l)(new)= Score(l)(old)- k*P
K is a constant and is set according to the study systems. Based on previous studies, appropriate value of k for this system was determined to be 32. 
