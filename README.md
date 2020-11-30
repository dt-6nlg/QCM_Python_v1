# PYTHON_DEV_QCM
## Part I
### Answer the following questions:

- Quelle est la difference ntre **Array** et **List** en Python ?  
==>

- Comment générer des nombres aléatoires en Python ?   
==>

- Comment comparer deux listes ?  
==>

- Quel module de Python est utilisé pour appliquer les méthodes liées au système d’exploitation ?   
==>

- Que fait l'instruction suivante ?
```python
print(2 in [1, 2, 3])
```
==>

- Que fait l'instruction suivante ?
```python
print([if i%2==0: i; else: i+1; for i in range(4)])
```
==>

- Que fait l'instruction suivante ?  
```python
list = [ 5, 'xyz' , 1.5, 90.3 ]
print(list[::-1])
```
==>

- Quelle est la sortie du code suivant ?   
```python
rnd = random.random()
print(rnd)
```
==>

- Quelle est la sortie du code suivant ?   
```python
str = “Hello World!”
print(str[1:4])
```
==>

- Quelle est la sortie du code suivant ?   

```python
list = [ 5, 'xyz' , 1.5, 90.3 ]
print(list[2:])
```
==>

- Quelle est la sortie du code suivant ?   
```python
tuple = ( 5, 'xyz' )
print(tuple * 2)
```
==>

- Comment récupérer toutes les *clés* d’un dictionnaire ?  
```python
dict = {'alex': 25,'bob': 22}
```
==>

- Comment récupérer toutes les *valeurs* d’un dictionnaire ?  
```python
dict = {'alex': 25,'bob': 22}
```
==>

## Part II

Fix the broken code and explain what was wrong:

```python
print([if i%2==0: i; else: i+1; for i in range(4)])
```
**FIX**
```python
# YOUR CODE HERE
```
What was wrong ==> 

## Part III
### Implement the following functions
```
is_prime
```
This function should accept a number and return True or False if the number is a prime number  
```python
is_prime(11) # True
is_prime(122) # False
```
**SOLUTION**
```python
# YOUR CODE HERE
```
-------------------------------------------------------------------------------------------

Assume you have a file called students.txt which simply contains a bunch of student names, one name per line. Your goal is to write two functions: 
- _add_student_ - accepts a parameter of first_name and writes to a file called _students.txt_.
- _find_student_ - accepts a parameter of first_name and returns the first student found

```python
add_student('Tom Ford')
find_student('Alibaba') # Alibaba was found!
```
**SOLUTION**
```python
# YOUR CODE HERE
```
