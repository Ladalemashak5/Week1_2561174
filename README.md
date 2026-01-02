📌 Overview

This C program demonstrates file handling using structures. It allows the user to:

Enter details of 5 products

Store product data in a file

Read and display product details from the file

Calculate the total bill

Search for a product by Product ID

The program uses binary file operations (fwrite, fread) to store and retrieve data.

🧾 Features

Uses struct product to store product information

Writes product records to a file (product.txt)

Reads all records and displays them in tabular format

Calculates and displays the grand total bill

Searches for a product using Product ID

🛠️ Technologies Used

Language: C

Concepts:

Structures

File Handling (FILE, fopen, fwrite, fread, fclose)

Loops and Conditional Statements

📂 File Description
File Name	Description
product.txt	Stores product records in binary format
📊 Structure Used
struct product
{
    int id;
    char name[30];
    int qty;
    double price;
    double total;
};
▶️ Program Flow

Open file in write mode

Accept details of 5 products from user

Calculate total price for each product

Store product data in file

Reopen file in read mode

Display all product details

Calculate and display total bill

Search product by Product ID

🧪 Sample Output (Conceptual)
Product Details
ID  Name   Qty  Price   Total
--------------------------------
1   Pen    10   5.00    50.00
2   Book   2    100.00  200.00
--------------------------------
Total Bill = 250.00
⚠️ Notes

The program uses conio.h, which is compiler-specific (mainly Turbo C / Windows).

Product name input does not support spaces.

File is opened in binary mode implicitly.

🎯 Learning Outcomes

 Understand how to use structures with files

 Learn binary file operations in C

 Practice searching records in a file
