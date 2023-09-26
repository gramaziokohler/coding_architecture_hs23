# Coding Architecture I: Week 02

This week, we will talk about iterable data types: lists, sets, tuples, as well as continue exploring different built-in functions. 

The goal of this week is to **understand and apply simple list algorithms**.


## Assignment 01

Details about submission are available on Moodle. The task and files required to solve it are below:

- [Assignment files](../../assignments/A01-area-checker/)


## Micro exercises

The following are very simple micro exercises that you can go through to practice some of the concepts of the current lecture. Each of them should not take more than 5 minutes to complete.

1. In a GHPython component with two input parameters `x` and `y`, with **item access**, write a program that sums both input parameters and prints the output.

2. In a GHPython component with one input parameter `numbers` with **list access**, write a program that sums all numbers and prints the output.

3. In the previous component, print the max and min values of the list.

4. In the previous component, print the median value of the list.

5. In the previous component, print the average of all values of the list.

6. In the previous component, print the list sorted in ascending order. Then print the list sorted in descending order.

7. In a GHPython component with two input parameters called `first_list` and `second_list`, both with **list access**, write a program that prints the pairs of elements of each list, eg. the first element of `first_list` with the first of `second_list`, then second element of `first_list` with the second of `second_list`, and so on.


<details>
  <summary><b>Solutions</b></summary>


1. 

```python
print(x + y)
```

2. 
    
```python
print(sum(numbers))
```

3. 

```python
print(max(numbers))
print(min(numbers))
```

4.
    
```python
numbers.sort()
median_index = len(numbers) / 2
print(numbers[mean_index])
```

or 

```python
median_index = len(numbers) / 2
print(sorted(numbers)[median_index])
```

5. 
    
```python
print(sum(numbers) / len(numbers))
```

6. 
    
```python
print(sorted(numbers))
print(sorted(numbers, reverse=True))
```


7. 

```python
for i, j in zip(first_list, second_list):
    print(i, j)
```

or 

```python
for i in range(len(first_list)):
    print(first_list[i], second_list[i])
```

</details>
