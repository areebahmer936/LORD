# Sorting Algorithms

- `n <- len(array)`
- `r <- range of keys`(i.e, max(key)-min(key)+1)
- `b <- base`

## dc__merge_sort

* [ ] in-place
* [x] stable (used equal operator with less or greater operator when comparing otherwise it tends to un-stable)
* Worst-case: `O(nlog(n))`
* Average-case: `O(nlog(n))`
* Best-case: `O(nlog(n))`
* Category: dc

## dc__merge_sort_iter

* no recursion depth problem
* [ ] in-place
* [x] stable (used equal operator with less or greater operator when comparing otherwise it tends to un-stable)
* Worst-case: `O(nlog(n))`
* Average-case: `O(nlog(n))`
* Best-case: `O(nlog(n))`
* Category: dc


## dc__quick_sort

* [x] in-place
* [ ] stable (un-stable, even if we check for equality)
* Best-case: `O(nlog(n))`
* Average-case: `O(nlog(n))`
* Worst-case: `O(n^2)` when already sorted with opposite `condition`
* Category: dc

## dc__quick_sort_iter

* no recursion depth problem
* [x] in-place
* [ ] stable (un-stable, even if we check for equality)
* Best-case: `O(nlog(n))`
* Average-case: `O(nlog(n))`
* Worst-case: `O(n^2)` when already sorted with opposite `condition`
* Category: dc


## insertion_sort

* [x] in-place
* [x] stable (equality must be checked)
* Best-case: `O(n)`
* Average-case: `O(n^2)`
* Worst-case: `O(n^2)`
* Category: ms

## selection_sort

(for non-decreasing)
In selection sort, start from index 0 intial say it's index(i.e 0) as smallest element index store this index
now search for the next(i.e, array[0] <= array[next])smallest element from 1 to n-1 replace this smallest element index to which we prev. stored
now after travelling to till the end(i.e, here n-1) replace the `0` element with smallest element(we know there index)
now repeat this process for index `1` then for index `2` and so on till the n-2

* [x] in-place
* [ ] stable (un-stable, even if we check for equality)
* Best-case: `O(n^2)`
* Average-case: `O(n^2)`
* Worst-case: `O(n^2)`

## bubble_sort

* [x] in-place
* [x] stable (equality must be checked) 	
* Best-case: `O(n^2)`
* Average-case: `O(n^2)`
* Worst-case: `O(n^2)`

## counting_sort

* Non-comparision sorting
* [ ] in-place
* [x] stable
* Best-case: `O(n+r)`
* Average-case: `O(n+r)`
* Worst-case: `O(n+r)`

## radix_sort

* Non-comparision sorting
* based on counting sort
* [ ] in-place
* [x] stable
* Best-case: O( (n+b)*log<sub>b</sub>(r) )
* Average-case: O( (n+b)*log<sub>b</sub>(r) )
* Worst-case: O( (n+b)*log<sub>b</sub>(r) )

## shell_sort

* modification of insertion sort
* [x] in-place
* [ ] stable
* Best-case: `O(nlog(n))`
* Average-case: -  
* Worst-case:  `O(n^2)`

## bucket_sort

* based on insertion sort
* [ ] in-place
* [x] stable
* Best-case: -
* Average-case: `O(n+r)`  
* Worst-case:  `O(r*(n^2))`


