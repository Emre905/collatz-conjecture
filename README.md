# Project goal:
Simple collatz conjecture analysis trying to find an infinite loop by getting the same term twice in the sequence

## Method:
- Play with the powers of 3 and 2 having $\dfrac{3^m}{2^n}$ and seeing how close it can get to 1
- Find sequences that has that m odd terms, n even terms (here m corresponds to having your number 3x+1, n is x/2)
- Compare first term with the m+n'th term

## Found Results:
Biggest case for terms with 1 difference: collatz(9233), having 9232 as 120th term

## Comments:
Since having 1 gap terms gets harder and harder when the numbers get bigger, it's likely that much bigger numbers will have bigger gaps and never be same
