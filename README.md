# Assignment-1-700763831-
NAME: SAI KEERTHI THUNGAPATI  ID#: 700763831

1)Write a program that takes two strings from the user: first_name, last_name. Pass these variables to fullname function that should return the (full name). o For example: ▪ First_name = “your first name”, last_name = “your last name” ▪ Full_name = “your full name” o Write function named “string_alternative” that returns every other char in the full_name string. Str = “Good evening” Output: Go vnn

Solution: This Python code takes the first and last name inputs from the user, concatenates them to form a full name, and then returns a modified version of the fullname where every other character is selected. The fullname function joins the first and last names with a space between them. The string_alternative function slices the string to return every second character using Python's slicing notation [::2]. In the main function, user input is gathered, the full name is printed, and the string with alternate characters is then displayed. For example, given the input "Ramakrishna" and "Ganta," the output will be "Full name: Ramakrishna Ganta" followed by "String with alternate characters: RmkihaGna".

2)Write a python program to find the wordcount in a file (input.txt) for each line and then print the output. o Finally store the output in output.txt file. Example: Input: a file includes two lines: Python Course Deep Learning Course Output: Python Course Deep Learning Course Word_Count: Python: 1 Course: 2 Deep: 1 Learning: 1

Solution: This code creates an input.txt file in Google Colab containing two lines of text: "Python Course" and "Deep Learning Course." It then defines a function word_count that reads the input.txt file, counts the occurrences of each word using Python’s Counter, and writes both the original content and the word count results into an output.txt file. The code first writes the lines of the input file to the output file, then calculates the word frequencies and appends them to output.txt. Finally, it prints the word count and displays the content of output.txt.

3)Write a program, which reads heights (inches.) of customers into a list and convert these heights to centimeters in a separate list using:

Nested Interactive loop.
List comprehensions Example: L1: [150,155, 145, 148] Output: [68.03, 70.3, 65.77, 67.13]
Solution: This Python code converts a list of customer heights from inches to centimeters using two different methods: a nested loop and list comprehension. In the main() function, the user is prompted to enter the number of heights and the heights themselves in inches. The program then uses the function inches_to_centimeters_nested() to perform the conversion through a loop, where each height is multiplied by 2.54 and rounded to 2 decimal places. Next, it uses inches_to_centimeters_list_comprehension() to achieve the same result using a more concise list comprehension. Both results are printed for comparison. If the input is invalid, the program displays an error message.
