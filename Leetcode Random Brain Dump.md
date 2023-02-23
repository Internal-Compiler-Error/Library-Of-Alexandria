    - if there is a *total order* defined on a set, then there is only *one* way to arrange any combinations of the elements from the set into a sorted sequence
	- counterintuitively, to count all the ways a subset (with potential replacements) of a set that follow the a particular order, you simply count the number of combinations
- knowing the count of something is actually very useful, it allows you to potentially define a bijection from a set that  you're more familiar with to the set you want to work on
- in recurrence relations, sums are distinct cases and products are nested loops!
    - I don't know what fraction denotes, perhaps grouping? (all the ones that are equivalent get reduced to one single case)

# Questions
- if we define a total order for a set, does that mean we can generate all the permutations easily by iterating them in order?
    - for the natural number set, up to n, such ordering already exists, the lexicographic order and algorithm that efficiently walks up and down the order also exist
    - it seems like no, there is an easy algorithm to generate the next permutation since every swap you make will result in a new valid permutation, but for a lot of sets this property won't hold

# Traps
```python
def a(x, y):
	if x < y:
		reutrn a(y, x)

	# logic
``` 
is actually stupid, it may look clean but once you enter the function call again, you do the exact check if you just performed again for no gain

