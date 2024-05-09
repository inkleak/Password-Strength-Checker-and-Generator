## Password Strength Checker and Generator

I am undertaking this project over Summer 2024 to attempt to recreate my GCSE Computer Science coursework from 2018. The premise of this project is very simple, to create a python script to check and generate passwords subject to a set of criteria. Some characters are not allowed. The list is below.

# Barred characters
Space " ", #, £, =, -, ;, :, <, >, all bracket types, /, \, `. 

The password also must not exceed 15 characters. The length of the password will be a parameter that can be modified for a password generation, but must not exceed 15 characters.

The strength of a password will be dependent on which characters are present within the sample. There are no consideration into if conventional words are coincidently placed within. For standard alphabet letters, standard english alphabet letters (d,e,f,g, etc) count as 1 point. Numbers count as 2, while "special characters" such as %,!,?,$,^,*,@ count for 5 letters. 

For a generation, generation is completely random, however a password with a score less than a value I haven't decided yet will not be approved and a new one must be generated which is above a threshold criteria.

I will be beginning this project in June 2024.

# Goals

- Create a password generation compartment irrespective of strength by June 21st 2024.
- Create an efficient algorithm for the the strength checker by July 2024.
- Complete the primary aims of the project by the end of July 2024.
- If possible, code a GUI for it! (Potentially August/September 2024)


