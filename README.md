# Kata2-ejerc-3
"""
Create a function that takes a string and returns the number (count) of vowels contained within it.
"""
def count_vowels(txt):
	sum = 0
	sum += txt.count('a')
	sum += txt.count('e')
	sum += txt.count('i')
	sum += txt.count('o')
	sum += txt.count('u')
	return sum
