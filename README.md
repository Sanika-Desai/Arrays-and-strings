# AIM
Strings

# THEORY

A string in C++ is a type of object representing a collection (or sequence) of different characters. Strings in C++ are a part of the standard string class (std::string). The string class stores the characters of a string as a collection of bytes in contiguous memory locations. Strings are most commonly used in the programs where we need to work with texts. We can perform various operations on the strings in C++. For example, reversing, concatenating, or passing as an argument to a function.

The syntax to create a string in C++ is quite simple. We use the string keyword to create a string in C++. However, we also need to include the standard string class in our program before using this keyword.

string str_name = "This is a C++ string";

# ALGORITHM

String Display
Start

Declare a string variable to store the input string (inputString).

Get the input string (inputString) from the user or from any source.

Use a for loop to iterate through the characters of the string:

Initialize a loop variable (i) to 0.
Continue the loop as long as i is less than the length of the string (inputString.length()).
In each iteration of the loop, print the character at index i.
Increment i after printing each character.
End

String Length
Start

Declare a string variable to store the input string (inputString).

Get the input string (inputString) from the user or from any source.

Initialize a variable (length) to 0. This variable will be used to count the characters in the string.

Use a for loop to iterate through the characters of the string:

Initialize a loop variable (i) to 0.
Continue the loop as long as the character at index i is not the null character ('\0').
In each iteration of the loop, increment the length variable by 1.
Increment i to move to the next character.
After the loop completes, the length variable will contain the length of the string.

Display or use the length as needed.

End

String Concatenation and Reverse String Concatenation

Concatenation Algorithm:

Start

Declare two string variables, str1 and str2, to store the input strings.

Get input for str1 and str2 from the user or from any source.

Declare a string variable, resultStr, to store the concatenated string.

Use a for loop to concatenate str1 and str2:

Initialize a loop variable (i) to 0.
Iterate through the characters of str1 using i and append each character to resultStr.
Repeat the above step for str2.
Display or use resultStr as needed.

End

Reverse Concatenation Algorithm:
Start

Declare a string variable, concatenatedStr, to store the concatenated string.

Get input for concatenatedStr from the user or from any source.

Declare two empty string variables, str1 and str2, to store the two original strings.

Calculate the length of the concatenatedStr.

Use a for loop to split the concatenatedStr into two original strings:

Initialize a loop variable (i) to 0.
Iterate through the characters of concatenatedStr using i.
Append each character to str1 until i reaches half the length of concatenatedStr.
Append the remaining characters to str2.
Display or use str1 and str2 as needed.

End

String Palindrome or not
Start

Declare a string variable to store the input string (inputString).

Get the input string (inputString) from the user or from any source.

Remove spaces and punctuation marks (if needed) from the input string to ensure accurate palindrome checking.

Declare two integer variables, left and right:

Initialize left to 0 (indicating the start of the string).
Initialize right to the length of the string minus 1 (indicating the end of the string).
Use a for loop to compare characters from the beginning and end of the string:

Initialize a loop variable (i) to 0.
Continue the loop as long as i is less than or equal to right.
In each iteration of the loop, compare inputString[left] and inputString[right]:
If they are not equal, the string is not a palindrome; break out of the loop.
If they are equal, increment left and decrement right to check the next pair of characters.
If the loop completes without breaking, the string is a palindrome.

Display a message indicating whether the string is a palindrome or not.

End

# OUTPUT

String Display

![image](https://github.com/Sanika-Desai/Arrays-and-strings/assets/142314095/85b11f53-d225-4b84-9e6b-857e20151157)

String Length

![image](https://github.com/Sanika-Desai/Arrays-and-strings/assets/142314095/521020e4-9a31-48fd-8848-7e759f5f35ca)

String Concatenation and Reverse String Concatenation

![image](https://github.com/Sanika-Desai/Arrays-and-strings/assets/142314095/e3eb0973-0df1-4f00-8c52-cb26897695b8)

String Palindrome or not

![image](https://github.com/Sanika-Desai/Arrays-and-strings/assets/142314095/fc4a2738-a81e-45a8-bd5d-8b3d0c7c3e0f)


# *EXPT 2*

# AIM
Arrays

# THEORY

In C++, an array is a data structure that is used to store multiple values of similar data types in a contiguous memory location.

For example, if we have to store the marks of 4 or 5 students then we can easily store them by creating 5 different variables but what if we want to store marks of 100 students or say 500 students then it becomes very challenging to create that numbers of variable and manage them. Now, arrays come into the picture that can do it easily by just creating an array of the required size.

# ALGORITHM

Enter the marks of 10 subjects and display it
Start

Declare an array to store the marks for 10 subjects (marksArray).

Use a for loop to iterate 10 times (for each subject):

Initialize a loop variable (i) to 0.
Continue the loop as long as i is less than 10.
In each iteration of the loop, prompt the user to enter the marks for the current subject and store it in marksArray[i].
Display the marks for each subject using a for loop:

Initialize a loop variable (i) to 0.
Continue the loop as long as i is less than 10.
In each iteration of the loop, display the marks for the current subject from marksArray[i].
End

Enter the marks of subjects from user and display it
Start

Declare variables for the number of subjects (numSubjects) and an array to store the marks (marksArray).

Prompt the user to enter the number of subjects (numSubjects).

Use a for loop to input marks for each subject:

Initialize a loop variable (i) to 0.
Continue the loop as long as i is less than numSubjects.
In each iteration of the loop, prompt the user to enter the marks for the current subject and store it in marksArray[i].
Display the marks for each subject using a for loop:

Initialize a loop variable (i) to 0.
Continue the loop as long as i is less than numSubjects.
In each iteration of the loop, display the marks for the current subject from marksArray[i].
End

C++ program to find the maximum and minimum value of given array
1.Start

2.Declare an array to store the elements (arr) and variables to store the maximum (max) and minimum (min) values.

3.Initialize max and min with the first element of the array (i.e., max = arr[0] and min = arr[0]).

4.Use a for loop to iterate through the array:

5.Initialize a loop variable (i) to 1 (assuming the first element has already been assigned to max and min).

Continue the loop as long as i is less than the length of the array.

In each iteration of the loop:

Compare arr[i] with max:

If arr[i] is greater than max, update max to arr[i].

Compare arr[i] with min:

If arr[i] is smaller than min, update min to arr[i].

After the loop completes, max and min will contain the maximum and minimum values in the array, respectively.

6.Display the maximum and minimum values.

7.End

C++ Program to find array Sum_Average
1.Start

2.Declare an array to store the elements (arr), a variable to store the sum (sum), and a variable to store the average (average).

3.Initialize sum to 0.

4.Use a for loop to iterate through the array:

5.Initialize a loop variable (i) to 0.

Continue the loop as long as i is less than the length of the array.

In each iteration of the loop:

Add arr[i] to sum.

5.Calculate the average by dividing the sum by the length of the array.

6.Display the sum and average.

7.End

To Flip Element
1.Start

2.Declare an array to store the elements (arr).

3.Get the elements of the array from the user or from any source.

4.Calculate the length of the array (length).

5.Use a for loop to flip the array:

Initialize two loop variables, start and end.

Initialize start to 0 (indicating the beginning of the array) and end to length - 1 (indicating the end of the array).

Continue the loop as long as start is less than end.

In each iteration of the loop:

Swap arr[start] and arr[end].

Increment start by 1.

Decrement end by 1.

6.After the loop completes, the array will be flipped.

7.Display the flipped array.

8.End

# OUTPUT

Enter the marks of 10 subjects and display it

![image](https://github.com/Sanika-Desai/Arrays-and-strings/assets/142314095/359ed791-b4f6-4e6c-b269-33579a1044bc)

Enter the marks of subjects from user and display it

![image](https://github.com/Sanika-Desai/Arrays-and-strings/assets/142314095/1d23ce3a-8465-44a7-93cd-6f37116312d2)

![image](https://github.com/Sanika-Desai/Arrays-and-strings/assets/142314095/7acdac3d-7cc6-438c-b266-e13a9c78efc0)

C++ program to find the maximum and minimum value of given array

![image](https://github.com/Sanika-Desai/Arrays-and-strings/assets/142314095/87634501-e166-4a43-a3a6-85e5a7fa611d)

C++ Program to find array Sum_Average

![image](https://github.com/Sanika-Desai/Arrays-and-strings/assets/142314095/19cb6b66-bd02-4479-b251-e2edbd21822b)

To Flip Element

![image](https://github.com/Sanika-Desai/Arrays-and-strings/assets/142314095/8c7b104c-c0ba-4184-bb32-ef8cf582087e)









