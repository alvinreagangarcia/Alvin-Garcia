1. ALPHABET SOUP

The initial procedure was to create a code that allows the user to input a word that would be ordered alphabetically.

alphabet = input('Enter a word: ')

Then a different function is used to equate it as the same value as the word to be input.

alphabet2 = list(alphabet)

Then the function will be sorted alphabetically by using .sort().

alphabet2.sort()

Since the function is a list, to remove the bracket and commas, the use of ''join() to stick all items in the list together.

''.join (alphabet2)

2. 
