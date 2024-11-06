# PY-Practical-5

1. string = "hello welcome to python"
character = input("Enter a character: ")
frequency = string.count(character)
print("Frequency of", character, "is", frequency)

'''output
Enter a character: e
Frequency of e is 3
'''

2. string = "hello welcome to python"
old_char = input("Enter the character to replace: ")
new_char = input("Enter the new character: ")
new_string = string.replace(old_char, new_char)
print("Modified string:", new_string)



'''output
Enter the character to replace: h
Enter the new character: t
Modified string: tello welcome to pytton
'''


3.string = "hello welcome to python"
char_to_remove = input("Enter the character to remove: ")
index = string.find(char_to_remove)
if index != -1:
    new_string = string[:index] + string[index + 1:]
    print("Modified string:", new_string)
else:
    print("Character not found in the string.")


'''output
Enter the character to remove: h
Modified string: ello welcome to python
'''


4. string = "hello welcome to python"
char_to_remove = input("Enter the character to remove: ")
new_string = string.replace(char_to_remove, "")
print("Modified string:", new_string)



'''output
Enter the character to remove: o
Modified string: hell welcme t pythn
'''
