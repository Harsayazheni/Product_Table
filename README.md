# Product Table
## Date:8/7/2025
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Product Table</title>
        <link rel='stylesheet' href="styles.css">
    </head>
    <body>
        <table>
            <caption>PRODUCT DETAILS</caption>
            <thead>
                <tr>
                    <th>Product Name</th>
                    <th>Product Price</th>
                    <th>Product Description</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Laptop</td>
                    <td>Rs.45000</td>
                    <td>High Speed Performance</td>
                </tr>
                <tr>
                    <td>Phone</td>
                    <td>Rs.36000</td>
                    <td>Good Quality Camera</td>
                </tr>
                <tr>
                    <td>Earbuds</td>
                    <td>Rs.5000</td>
                    <td>Noise Cancellation</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
```
## Output:
![image](https://github.com/user-attachments/assets/e538a695-0f4a-4ba9-87c6-5381eeb36e8c)

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
