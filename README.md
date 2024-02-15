# Author: Michelle Frugia
# GitHub username: frugiam
# Date: 02/14/2024
# Description: Project 6b


def add_surname(first_names_list):
    # Create a new list (full_list) using a list comprehension.
    # Append ' Kardashian' to each name in the input list only if the name starts with the letter 'K'.
    full_list = [name+' Kardashian' for name in first_names_list if name[0] == 'K']
    # Return the resulting list with added surnames.
    return full_list

# Sample list of first names.
first_names_list=["Kiki","Krystal","Pavel","Annie","Koala"]

#Calling of the add_surname function along with the sample lit and print the result.
print(add_surname(first_names_list))
