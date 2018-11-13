
functions are the first class objects. They can be passed as arguments to other functions and returned as values from the functions. They can be assigned to variables and stored as data structures


```python
def add_func(a,b):
    return a+b
def mul_func(a,b):
    return a*b
def div_func(a,b):
    return a//b
def mod_func(a,b):
    return a%b
list_func = [add_func,mul_func,div_func,mod_func]

for i in range(len(list_func)):
    print(list_func[i](6,3))


```

    9
    18
    2
    0
    
