Download Link : https://programming.engineering/product/ve477-homework-4/

# VE477-Homework-4
VE477 Homework 4

Questions preceded by a * are optional. Although they can be skipped without any deduction, it is important to know and understand the results they contain.

Ex. 1 — Time vs. space

The goal of this exercise is to consider the best available hardware and compare the feasibility of heavy computation in terms of (i) time and (ii) memory.

    As of June 2015 the fastest supercomputer publicly known is called NUDT Tianhe-2. Its speed is 33.86 PFLOPS and its storage is 12.4 PB1.

    As of August 2015 one of the fastest CPU for desktop computer is the Intel Core i7-5775R Processor which has four core running at maximal frequency of 3.8 GHz2.

    As of August 2015 the largest hard drive is almost 16TB3.

        How long would it take to perform 264 operations on NUDT Tianhe-2? What about 280 opera-tions?

        How many desktop computers would be necessary to perform 264 operations in no more than a day. What about 280 operations in no more than a month?

        How many hard drives would be necessary to store 264 bits. What about 280 bits?

Ex. 2 — Critical thinking

Given a set S of n integers, generate a subset S′ of S composed of k elements, each selected with probability k/n. Explain how to obtain S′ in only one pass.

Ex. 3 — Algorithm and complexity

In the following triangle each entry is the sum of the three entries directly above it.

                        				

                        1
                        				
                        			

                        1
                        	

                        1
                        	

                        1
                        			
                        		

                        1
                        	

                        2
                        	

                        3
                        	

                        2
                        	

                        1
                        		
                        	

                        1
                        	

                        3
                        	

                        6
                        	

                        7
                        	

                        6
                        	

                        3
                        	

                        1
                        	

                        1
                        	

                        4
                        	

                        10
                        	

                        16
                        	

                        19
                        	

                        16
                        	

                        10
                        	

                        4
                        	

                        1

    Write the pseudo-code of a simple algorithm which returns the sum on all the elements in the i-th line, when given i as input.

Determine the complexity of this algorithm, and prove its correctness. * Ex. 4 — From SAT to 3-SAT

Rewrite the following SAT formula into a 3-SAT formula.

(x1 ∨x2 ¬x3 ∨x4 ∨x5 ¬x6) ∧(¬x1 ¬x2 ∨x3 ¬x4 ∨x5 ∨x6) ∧(x1 ¬x2 ¬x3 ∨x4 ∨x5 ¬x6) ∧(x1 ¬x2).

Ex. 5 — Clique problem

    1. Explain what the Clique problem is.

        Prove that Clique is in N P.

        Given a 3-SAT formula F with k clauses, construct a graph G such that F is satisfiable if and only if G has a k-clique.

        Conclude on the complexity class of the Clique problem.

Ex. 6 — IND-SET problem

    1. What is the maximum independent set problem?

        What is the independent set (IND-SET) decision problem?

        Prove that IND-SET is in N P.

        Construct a graph G ′ such that “G has a k-clique” is equivalent to “G ′ has an independent set of size k”.

        Conclude on the complexity class of the IND-SET problem.

