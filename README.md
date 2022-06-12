```python
# jupyter nbconvert --to markdown 00py_oop.ipynb --output README.md

```

# Python Basic

## Expression vs Statement


```python
iq=100
user_age=iq/100 # iq/100 is a Expression and full is statement
```

## Agument assignment opeerator



```python
some_value=10
some_value+=10 # some_value=some_value+10
some_value*=10 # some_value=some_value*10
print(some_value)
```

    200
    

## String

### String concatenation and type conversion


```python
# print("hello"+"world"+5)
print("hello"+"world"+str(5))
a=str(5)
b=int(a)
c=type(b)
print(c)

```

    helloworld5
    <class 'int'>
    


```python
## Escape Sequences
weather = "It\'s \"kind off\" sunny today"
print(weather)
```

    It's "kind off" sunny today
    

## formatted string


```python
name = "John"
age=45
print("hi "+name+" you are "+str(age))
print("hi %s you are %d" %(name,age))
print(f'hi {name} you are {age}')
print('hi {0} you are {1}'.format(name,age))
```

    hi John you are 45
    hi John you are 45
    hi John you are 45
    hi John you are 45
    
