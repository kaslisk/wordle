i love wordle :)

i hate losing >:(

so i made use of the bron kerbosch algorithm to find n-word chains, 1 <= n <= 5, that all contain unique letters. the problem can be reduced into a maximal clique problem if we make every vertex of a graph to be a word and construct edges
between all pairs of words if they do not share any characters. is np complete so takes a while to run. pls lmk if any optimizations can be made i want this to be scalable for n letters. 

also looking to find ways to optimize guesses based on made guesses.
