## 1.


```python
marks = int(input("Enter the percentage:"))
if marks > 90:
    print("you have got: A Grade")
elif marks> 80 and marks<= 90:
    print("you have got: B Grade")
elif marks >= 60 and marks<=80:
    print("you have got: C Grade")
else:
    print("you have got: D Grade")
    
```

## 2.


```python
price = int(input("Enter the cost price of bike:"))
if price>100000:
    tax = (price/100)*15
    print(f"you have to pay 15% road tax of cost price.And ammount to be paid:{tax}")
elif price > 50000 and price<=100000:
    tax = (price/100)*10
    print(f"you have to pay 10% road tax of cost price.And ammount to be paid:{tax}")
else:
    tax = (price/100)*5
    print(f"you have to pay 5% road tax of cost price.And ammount to be paid:{tax}")
```

## 3.


```python
city = input("Choose the city name Delhi, Agra or Jaipur:")
city = city.capitalize()
if city =="Delhi":
    print("Monument : Red Fort")
elif city=="Agra":
    print("Monument : Taj Mahal")
elif city=="Jaipur":
    print("Monument : Jal Mahal")
else:
    print("Please choose the given city name")
```

## 4.


```python
number = int(input("Enter number:"))
if number <=10:
    print("the number is less then or equal to 10")
else:
    result=number//3
    print(f"the number can be divided by {result} times")
```

## 5.

A while Loop is used to repeat a specific block of code an unknown number of times. Until a condition is met. For example, if we want to ask a user for a number between 1 and 10, we don't know how many times the user may enter a larger number, so we keep asking while the number is not between 1 and 10


```python
#EXAMPLE
while True:
    number = int(input("Enter number between 1 to 10:"))
    if number<=10 and number>=1:
        print("You have entered correct number")
        break
    else:
        continue
```

## 6.


```python
n = int(input("Enter number:"))
i = 1
j = 0
while i<=n:
    while j<=i:
        print(str(j)*j)
        j = j+1
    i = i+1
        
```


```python
n = int(input("Enter pattern size number:"))
i = 1
while i <=n:
    j =1
    while j<=i:
        print("*",end = " ")
        j=j+1
    i = i+1
    print()
    
```


```python
n = int(input("Enter number:"))
i = 1
while i<=n:
    j = n
    while j>=i:
        print("*",end = " ")
        j = j-1
    i =i+1
    print()
```

## 7.


```python
i=10
while i>=1:
    print(i)
    i-=1      
```

## 8.


```python
i=10
while i>=1:
    print(i)
    i-=1  
```


```python

```
