# Experiment 1
1. ALPHABET SOUP

The initial procedure was to create a code that allows the user to input a word that would be ordered alphabetically.
```python
alphabet = input('Enter a word: ')
```
Then a different function is used to equate it as the same value as the word to be input.
```python
alphabet2 = list(alphabet)
```
Then the function will be sorted alphabetically by using .sort().
```python
alphabet2.sort()
```
Since the function is a list, to remove the bracket and commas, the use of ''join() to stick all items in the list together.
```python
''.join (alphabet2)
```

2. EMOTICON PROBLEM

The initial process was to set "mood" as a string.
```python
mood = str('I am happy')
```
Then use .replace() to replace "happy" to ":)"
```python
mood.replace("happy",":)")
```

3. UNPACKING LIST PROBLEM

1st step was to set values to the list.
```python
list = ['1', '2', '3', '4', '5', '6', '7', '8']
```
Then use the command list[0] and print("First: ",list[0]) to print thre first value of the list
```python
list[0]
```
```python
print("First: ",list[0])
```
Then the same process for the middle and last value of the list
```python
list[1:6]
```
```python
print ("Middle: ",list[1:6])
```python
list[7]
```
```python
print ("Last: ",list[7])
```

