---
description: Writeup of my feature for CPT.
title: CPT Write Up
toc: true
categories: [markdown]
layout: post
---

# Write-Up (Marketplace)
## 3a.
### 3.a.i.
This program is meant to provide a more streamline system for business managers to store their company's inventory/products. Users can also view these products if they are interested in purchasing.
### 3.a.ii.
This program allows a user to input various attributes of their product such as name, cost, and stock as well as date. My program then generates a ID which is set according to the time the entry was placed. This program is available for all users so it functions as a marketplace, allowing users to search for products they may want to buy.
### 3.a.iii.
The inputs of the program are the user’s typed entries into the form for which entries are made. The program collects this data and returns an input stating whether or not the inventory was successfully added - depending on if the user’s entries met the requirements such as filling out all fields - and then may be called upon to displays its entries within the search feature that neatly formats the attributes in a table.
## 3.b
### 3.b.i.
<img src="{{site.baseurl}}/images/Screenshot (107).png" alt="Code" style="width:250px;height:350px;">

### 3.b.ii.
<img src="{{site.baseurl}}/images/Screenshot (108).png" alt="CodeProcedure" style="width:325px;height:450px;">

### 3.b.iii.
The variables stored are titled respectively through the form box. They are titled product, cost, and stock. There is also ID which is set to current time value.
### 3.b.iv. 
All the variable in my list ar important to my program because they represent unique and necessary aspects of a product such as it's name, cost, and how much of the product you have aka stock. It is necessary in order to take read and create data.
### 3.b.v
By storing the variables respectively, I manage complexity by preventing duplicate or mistaken values. If my values were the same, I would have conflicting values in my database which would likely lead to it being disfunctional. To fix this through a different method, I would have to lengthen my code and make it more complex.
## 3.c
### 3.c.i.
<img src="{{site.baseurl}}/images/Screenshot (108).png" alt="CodeProcedure" style="width:325px;height:450px;">

### 3.c.ii.
<img src="{{site.baseurl}}/images/Screenshot (107).png" alt="Code" style="width:250px;height:350px;">

### 3.c.iii.
The procedure here is addProduct. It retrieves the user input from the formboxes. When the 'click' is made on each respective button the input from the user is stored and placed into a database which is then displayed within the input field. Also, the program gets elements by their id which is product, cost, and stock respectively.
### 3.c.i.v
<img src="{{site.baseurl}}/images/Screenshot (110).png" alt="CodeMain" style="width:400px;height:550px;">
The code defines a function addProduct which starts by collecting input data from a web form using document.getElementById. The function then proceeds to use selection to check if the username field is empty, and if it is, it displays an alert to the user and returns from the function. If the username field is not empty, the function constructs a data object using sequencing, which contains the input values collected earlier. The function then constructs a requestOptions object also using sequencing which includes the data object, and specifies the HTTP method and content type headers for a POST request.

## 3.d
### 3.d.i
The user inputs the attributes of their product and clicks on the “addProduct” button. The first call to addProduct procedure passes a command to get and store user input into the system. This call will execute the entire algorithm, constructing the data object, constructing the requestOptions object, and sending a POST request to the specified URL with the data object as the request body. If the request is successful, a success message will be logged to the console and an alert will be shown to the user indicating that the inventory has been added.

### 3.d.ii
Conditions for user input manages our program's recieved input. These conditions are enforced by the placeholders. They make sure user input match the requested structure so that no false input goes in. The second last command of my program enforces that there is something to call back to. Pattern also helps recieved data to mach the specific formatting. Each of these test cases executes different parts of the algorithm, going by the condition of which input fields are filled out for each attribute.

# Peer Review Scores and Feedback
[Peer Grades](https://github.com/JonathanWuz/Jonathan-Wu-s-Repository/issues/33)