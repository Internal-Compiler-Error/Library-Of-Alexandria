- if there is a *total order* defined on a set, then there is only *one* way to arrange any combinations of the elements from the set into a sorted sequence
	- counterintuitively, to count all the ways a subset (with potential replacements) of a set that follow the a particular order, you simply count the number of combinations
# Questions
- if we define a total order for a set, does that mean we can generate all the permutations easily by iterating them in order?
    - for the natural number set, up to n, such ordering already exists, the lexicographic order and algorithm that efficiently walks up and down the order also exist
# Traps
```python
def a(x, y):
	if x < y:
		reutrn a(y, x)

	# logic
``` 
is actually stupid, it may look clean but once you enter the function call again, you do the exact check if you just performed again for no gain

