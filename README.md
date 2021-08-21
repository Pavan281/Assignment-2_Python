# Assignment-2_Python-Python Zero to Hero
# Take a string input and print the number of occurrences of each character.
# e.g: If string is "hello" then output should be h - 1, e - 1, l - 2, o - 1.
def char_frequency(str1):
    dict = {}
    for n in str1:
        keys = dict.keys()
        if n in keys:
            dict[n] += 1
        else:
            dict[n] = 1
    return dict
print(char_frequency('hello'))

# OUTPUT : {'h': 1, 'e': 1, 'l': 2, 'o': 1}
