Embedding and Transformer Synthesis

This repo contains my code submission for Apart Research's Alignment Jam 3.0 (a 3-day July 2023 hackathon).  

Here is a link to my writeup: https://docs.google.com/document/d/1Hk1NQSQE3ycaDRULxB-Cy78FuqFW9sUDIEc_56UMlMI/

Here is a link to the hackathon: https://alignmentjam.com/jam/interpretability

Quick Summary (copied from my above link):

Prior to this hackathon, I had a (low-level) mechanistic interpretability hypothesis about how a specific 1-layer transformer trained on a specific classification function might work. 

For this hackathon: 
- I programmatically created a set of embeddings that can be used to perfectly reconstruct the original classification function (“embedding synthesis”).
- I used these embeddings to programmatically set weights for a 1-layer transformer that can perfectly reconstruct the original classification function (“transformer synthesis”). With one change, this reconstruction matches my original hypothesis of how the pre-existing transformer works.
- I ran several experiments on my synthesized transformer to begin to evaluate my hypothesis.  I am slighty less confident in my original hypothesis as a result of the experiments (though I think it may be close).
- A jupyter notebook can be viewed here on github.

