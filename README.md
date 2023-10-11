# More-on-list
More on list 



#     Write a Python program that accepts a hyphen-separated
# sequence of words as input and prints the words in a hyphen-separated
# sequence after sorting them alphabetically.
#
# Sample input string : green-red-yellow-black-white
hyphen_separated_sequence = input("Please enter your sequence: >>>\n")
sequence = hyphen_separated_sequence.split("-")
sequence = "-".join(sorted(sequence))
print(sequence)
