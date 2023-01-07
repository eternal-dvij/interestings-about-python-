# Interestings-about-python-
Here are some interesting things about python



## DataStructures
### Python have these bilt-in data structures: list- [],dictionary- {"key":value},tuples- () and set- {} {the miracle still not updated here)
```python
s = "hello you there! see the python miracle"
x = list[s]
set(x)

```

-------------------------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------------------------

## type() function in python (POV JUPYTER)
### if you are using type() anytimes in a single block of code, it will output the result for the last called type() as below:

```python
v = 'hello xyz'
i = "hello zbcg hi"
inj = 67
print(type(v))
print(i)
type(i)
type(inj)

```
#### output:
<class 'str'>
<br>hello zbcg hi

int

#### explore more in jupyter for this (hint: out in jupyter)

-------------------------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------------------------

### indexing and slicing, start index could be greater than the length of string but it will just fetch the result from the last(no matter if it is greater)
```python
v = 'hello xyz'
i = "hello zbcg hi"
i[19:0:-1]

```
#### output:
'ih gcbz olle'

-------------------------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------------------------

## jupyter objection- if you have used a function in the end of block then at "out" it will show result of only that
e.g:
```python
v = 'hello xyz'
i = "hello zbcg hi"
inj = 67
i[19:0:-2]
len(i)

```

#### output
13
