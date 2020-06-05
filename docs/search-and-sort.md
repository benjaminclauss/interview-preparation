### Binary Search
```
def binary_search(array, target):
	n = len(array)
	low = 0
	high = n - 1
	
	while low <= high:
		mid = (low + high) // 2
		if array[mid] < target:
			low = mid + 1
		elif array[mid] > target:
			high = mid - 1
		else:
			return mid

	return -1
```