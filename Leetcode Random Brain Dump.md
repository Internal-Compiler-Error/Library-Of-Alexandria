- if there is a *total order* defined on a set, then there is only *one* way to arrange any combinations of the elements from the set into a sorted sequence
	- counterintuitively, to count all the ways a subset (with potential replacements) of a set that follow the a particular order, you simply count the number of combinations

# Traps
```python
def a(x, y):
	if x < y:
		reutrn a(y, x)

	# logic
``` 
is actually stupid, it may look clean but once you enter the function call again, you do the exact check if you just performed again for no gain

