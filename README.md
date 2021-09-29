python-flow-control
===
CH 1. Flow Control Overview & Boolean & Comparison Operator 
---
<br>Flow Control : Conditional & Loop

<br>Boolean: True or False

<br>Comparison Operators: ==, >, <, >=, <=, !=

* '=' is an assignment operator

***
Ch 2. Conditional Statement
---
1-1. if basics
* if the statement after if is false, it does not print anything

1-2. if practice problem
* Create a variable called input_id, receive input as input, and print a specific phrase if it matches the value stored in the variable called id.

2-1. if else
* If the conditional statement is False, print the value after else:.

2-2. else practice problem
* If you receive a value other than egoing stored in the id variable as input_id, print Who?

3-1. elif
* If the if statement is false, it goes over to the elif statement.
* If eliff statement is also false, print the value after else:.

3-2. elif practice problem
* Make two id variables, and if the value entered in input_id matches at least one, print Welcome, if it does not match both variables, print Who?

4-0. if in the if
* Using the if in the if, the id in the first if and the password in the second if must match to print Welcome.

***
Ch 3. Loop
--- 

* Loop and lists go together

<br>1. For statement

        for (value) in [1,2,3]

print (value) # print 1,2,3 in order 

<br>2. Multi-dimensional lists
<br><br>One-dimensional list

    ['egoing','basta',blackdew'] 

 Two-dimensional list

    [['egoing','Seoul','Web'],['basta','Seoul','IOT'],['blackdew','Tongyeong','ML']]

 * putting variable names directly after "for" makes code interpretation better

        for name, address, interest in names:


<br>3. dictionary

        {'name':'egoing', 'address':'Seoul', 'interest':'Web'}

Dictionary that matches key and value

*for key in person: <br>print(key) will print dictionary's key, <br>person[key] will print key's value in the dictionary

