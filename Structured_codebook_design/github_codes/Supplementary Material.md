# Supplementary Material  

The GA results under different parameter settings:

![image-20241025155313343](C:\Users\13727\AppData\Roaming\Typora\typora-user-images\image-20241025155313343.png)



The above figure compares the GA results under different parameter settings. Under the  same SCMA system scales, GA parameters are identical except for the population size. To display the GA results of different SCMA systems in the same figure, we multiplied the results of the $4\times 6$ SCMA system by $10^6$, while the results of the $5 \times 10$ SCMA system were multiplied by $10^4$. As seen from this figure, for both $4\times 6$ and  $5\times 10$ SCMA systems, the population size and generations of $200$ are sufficient for codebook optimization. Specifically, the population size of $400$ generates better initial results compared to the population size of $200$ under different SCMA systems. However, as the number of generations increases, the gap between the optimal results for different population sizes narrows, showing a similar trend. Further, since the $5 \times 10$ SCMA system adopts a partial Euclidean distance spectrum as the design metric, the GA results do not always decrease steadily and may exhibit occasional spikes and dips.