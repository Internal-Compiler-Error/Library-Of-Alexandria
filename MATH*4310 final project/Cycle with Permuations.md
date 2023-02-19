# Definition
Also called a cyclic permutation, given a set $X$, $S \subseteq X$ is a permutation that maps elements in $S$ to other elements in $S$. $k :=|S|$ and such permutation is called a k-cycle permutation. 

Note a mapping that maps to itself is called a fixed point and typically not considered as a cycle.

## Example
For example, given $X = \{1,\ 2,\ 3,\ 4\}$, the permutation $(1,\ 3,\ 2,\ 4)$ that sends 1 to 3, 3 to 2, 2 to 4 and 4 to 1 (so $S = X$) is a 4-cycle.

That is to say, given two consecutive positions in the permutation, $[i] \rightarrow [i + 1 \mod k]$. 

## Orbit
$S$ is also called the orbit of the cycle. 
> Every permutation on finitely many elements can be decomposed into cycles on disjoint orbits.

No idea what it means

# Notation
Using [[Two-line notation of Permutations]], each column becomes the top element mapping to the bottom element. Some author will also arrange the column in such a way that for each row, $[i] \rightarrow [i+ 1|$.

