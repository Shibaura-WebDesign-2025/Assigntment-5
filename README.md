# Assignment-5

## Introduction to PHP

## How to upload your homework?

# SFTP Login and Upload Instructions

1. **Download and install FileZilla Client**  
   Visit [FileZilla’s official website](https://filezilla-project.org/) and download the appropriate version for your operating system. Follow the installation instructions.

2. **Login to your account**  
   Open FileZilla and enter the following details in the top bar:

   - **Host**: `sftp://172.21.82.208`  
   - **Username**: Your ID (with a capital letter, e.g., `Zxxx`)  
   - **Password**: Use the given password

   Click **Quickconnect** to establish the connection.

3. **Upload your assignment**  
   - Create and upload your folder for each assignment.  
   - Example folder structure:  
     ```
     xxxxx/Assignment_5/part1/index.php
     ```
     where `xxxxx` is your user ID.

4. **Start transferring files**  
   After creating your folder, drag and drop your files into it using the FileZilla interface.

> **Note**: If you have any connection issues, please contact the system administrator.


 <img  alt="Screenshot 2024-06-04 at 17 22 46" src="https://github.com/user-attachments/assets/92ee55e0-8d98-421a-85b2-01e57a1c99ea">

# Part 1

**Creating a Simple Calculation Program using PHP**

In this exercise, you will apply your knowledge of PHP to create a simple calculation program. You will use variables to store values and perform calculations, and then display the results on a web page.

1. With the given index.php, please fill in necessary PHP code to define a variable and perform calculations.
2. Calculate the sum of the numbers 100, 1050, and 200 and store it in **a variable**.
3. Use another PHP code block to display the calculated sum on the web page.
4. Below the sum calculation, write additional PHP code to calculate the tax-inclusive amount (8% and 10%).
5. Use another PHP code block to display the tax-inclusive amount on the web page.
6. Save index.php file
7. Upload your PHP files in your respective folder :Assignment5_Part1
8. You can check how the look like from http://172.21.82.208/your_user_ID/Assignment5_Part1(change_with_necessary_folder_name)/part1/index.php

> You can check how the correct webpage should look like from http://172.21.82.208/gift/class6/sol/part1/index.php


# Part2

**Display Numbers from 1 to 365 using PHP**

In this exercise, you will use your knowledge of PHP to display numbers from 1 to 365 on a web page. You will be required to write the PHP code that performs the necessary calculations.

1. With the given index.php, please fill in necessary PHP code to define a variable and perform calculations.
2. Inside the `<pre></pre>` tags, you will write PHP code to display numbers from 1 to 365.
3. Using a suitable PHP loop construct, write the necessary code to loop through the numbers from 1 to 365.
4. Create a variable to store each number in the loop.
5. Display each number on a new line using the `print()` or `echo` statement.
6. Save index.php file
7. Upload your PHP files in your respective folder :Assignment5_Part2

> You can check how the correct webpage should look like from http://172.21.82.208/gift/class6/sol/part2/index.php


# Part 3

**Experiment with PHP arrays**

In this homework assignment, you will practice working with PHP arrays. You will perform various operations on arrays, such as creating, using array functions.

> Hint: The ksort() function is used to sort the associative array $fruits by its keys in ascending order.

1. With the given part3.php, please fill in necessary PHP code.
2. Create the associative array by inputting romaji for each English word
3. Use another PHP code block to display result of your associative array using foreach function
4. Use another PHP code block to sort the array using ksort and display again.
5. Save index.php file
6. Upload your PHP files in your respective folder :Assignment5_Part3

> You can check how the correct webpage should look like from http://172.21.82.208/gift/class6/sol/part3/index.php

# Part 4

**Getting input and output using Forms**

In this exercise, you will write the PHP code that gets input from a form and displays the output.

**Open and test the application**

Open and test application by running the index.php file

Write the code that gets and displays the data entered by the user

**You need to edit display_result.php file**

**Can you try to**

1. Add the code that gets the data from the controls on the first page. Then, add the code that displays this data.
2. For the radio buttons, display a value of “Unknown” if the user doesn’t select a radio button.
3. For the check box, display a value of “Yes” or “No” depending on whether the user has selected the check box.
4. For all fields that allow the user to type text into the field, make sure to convert special characters into HTML entities before displaying that data on the second page by using the php function htmlspecialchars()
5. For the comment field, make sure to convert new line characters to <br> tags so the web page can display new line characters correctly.
6. Test the application to make sure it works correctly. To do that, you can test text fields with special characters such as the ampersand (&), and you can press the Enter key in the comments field to enter a new line character.
7. Save **display_result.php** file
8. Upload your PHP files in your respective folder :Assignment5_Part4

> You can check how the correct webpage should look like from 
http://172.21.82.208/gift/class6/sol/part4/index.php

# Part 5

**Getting the order using PHP Form**

**You need to edit pizza.php file**

1. Open the HTML file (index.html)
2. Can you modify the PHP code in pizza.php so that it would receive the information the user input in the form shown in index.html?
3. Save pizza.php file
4. Upload your PHP files in your respective folder :Assignment5_Part5

   
<img width="480" alt="Screenshot 2024-06-05 at 16 49 30" src="https://github.com/Shibaura-WebDesign-2024/Assignment-4/assets/166518626/fae6d772-a569-4f13-abf2-bd527825bc7a">

The input example on index.html

<img width="470" alt="Screenshot 2024-06-05 at 17 01 23" src="https://github.com/Shibaura-WebDesign-2024/Assignment-4/assets/166518626/a855299f-bf51-48a7-ab99-e18d4a4bb318">

The resulting page (pizza.php) after taking the input above

> You can check how the correct webpage should look like from 
http://172.21.82.208/gift/class6/sol/part5/index.html
