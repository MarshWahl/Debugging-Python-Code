# Debugging-Python-Code
In this project, I will demonstrate a few different forms of errors within Python Code and how to resolve them.

### Syntax Error
![image](https://github.com/user-attachments/assets/dee11560-dd79-4813-b27c-2a50dc640b36)
Running the initial code outputs a SyntaxError in line 3. This error can be resolved by locating line 3, analyzing the line for proper syntax, and correcting the syntax. In this case, within the `usernames_list`, one of the elements does not end with a " and , allowing that element and the remaining elements to not be registered in the list properly. Adding the proper syntax for a list resolves the Syntax Error.

![image](https://github.com/user-attachments/assets/542dfcfd-b9dc-4cff-a562-e3b3882a44f3)
Running the initial code outputs an Indentation Error, which is a subclass of SyntaxErrors, in line 17. Here, the `print()` function is excluded from the `if` statement. Indenting line 17 one space includes it into the `if` statement, resolving the error.

### Exception Error
![image](https://github.com/user-attachments/assets/73fecaac-bd85-4a91-a098-03d39fbee626)
Running the inital code outputs a NameError, which is a type of ExceptionError, in line 11. Here, `username_list` is not defined. Backtracking to the creation of the variable, we see there has been a misspelling of the variable in line 11. Correcting it to `usernames_list` resolves this error.

![image](https://github.com/user-attachments/assets/45019a5b-b65d-4bbc-9c86-f9016fe36a7f)
Running the initial code results in an IndexError, which is a type of ExceptionError, in line 12. The IndexError notes that the list index is out of range. Looking at the list being called, there are only 4 indices, 5 elements total. To fix this error, we can change the bracketed `5` to match the length of the `usernames_list`, which is 4.

### Logic Error
![image](https://github.com/user-attachments/assets/613e0424-e399-410a-acf9-f7376f42321b)
Running the code before modification results in `OS 2` outputting a patch date of March 1st, which is incorrect. Analyzing the `if` loop and `elif`'s, we see that the `patch_schedule` indices for `OS 1` and `OS 2` are incorrect, pulling the wrong elements from `patch_schedule`.
These logic errors can be resolved by replacing the incorrect indices with the correct ones.
