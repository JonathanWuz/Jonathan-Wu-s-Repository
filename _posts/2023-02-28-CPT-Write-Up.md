---
description: A blog post reflection of the event, Night at The Museum.
title: N@TM Blog Posrt
toc: true
categories: [markdown]
layout: post
---

# Write-Up (Marketplace)
## 3a
### 3.a.i.
This program is meant to provide a more streamline system for business managers to organize and locate their company’s inventory.
### 3.a.ii.
This program allows a user to not only input entries regarding various attributes of their company’s inventory, such as the price of the product, how much it costs to produce, how long it takes to deliver, the quantity, and any other extra notes. The user does this by first defining under what company name this inventory goes under. This is useful because the feature also allows a search feature, where a user may type in the name of a specific company, and any entries made under that name will appear in a neat, organized table that displays each attribute. These entries are all persistent as well, so even if the page is closed and reopened, the entries remain.
### 3.a.iii.
The inputs of the program are the user’s typed entries into the form for which entries are made. The program collects this data and returns an input stating whether or not the inventory was successfully added - depending on if the user’s entries met the requirements such as filling out all fields - and then may be called upon to displays its entries within the search feature that neatly formats the attributes in a table.
## 3.b
### 3.b.i.
![]({{site.baseurl}}/images/Screenshot (107).png)
### 3.b.ii.
![]({{site.baseurl}}/images/Screenshot (108).png)
### 3.b.iii.
The variables stored are titled respectively through the form box. They are titled product, cost, and stock. There is also ID which is set to current time value.
### 3.b.iv. 
All the variable in my list ar important to my program because they represent unique and necessary aspects of a product such as it's name, cost, and how much of the product you have aka stock. It is necessary in order to take read and create data.
### 3.b.v
By storing the variables respectively, I manage complexity by preventing duplicate or mistaken values. If my values were the same, I would have conflicting values in my database which would likely lead to it being disfunctional. To fix this through a different method, I would have to lengthen my code and make it more complex.
## 3.c
### 3.c.i.
![]({{site.baseurl}}/images/Screenshot (108).png)
### 3.c.ii.
![]({{site.baseurl}}/images/Screenshot (107).png)
### 3.c.iii.
The procedure here is addProduct. It retrieves the user input from the formboxes. When the 'click' is made on each respective button the input from the user is stored and placed into a database which is then displayed within the input field. Also, the program gets elements by their id which is product, cost, and stock respectively.
### 3.c.i.v
![]({{site.baseurl}}/images/Screenshot (103).png)
The code defines a function addProduct which starts by collecting input data from a web form using document.getElementById. The function then proceeds to use selection to check if the username field is empty, and if it is, it displays an alert to the user and returns from the function. If the username field is not empty, the function constructs a data object using sequencing, which contains the input values collected earlier. The function then constructs a requestOptions object also using sequencing which includes the data object, and specifies the HTTP method and content type headers for a POST request. The function then uses iteration, in the form of a try-catch block, to handle errors that may occur during the fetch request. Finally, the function uses fetch to send a POST request to a specified URL and logs the success response to the console, as well as displaying an alert to the user.

## 3.d
### 3.d.i
The user inputs the attributes of their desired inventory and clicks on the “addProduct” button. The first call to addProduct procedure passes a command to get and store user input into the system. This call will execute the entire algorithm, constructing the data object, constructing the requestOptions object, and sending a POST request to the specified URL with the data object as the request body. If the request is successful, a success message will be logged to the console and an alert will be shown to the user indicating that the inventory has been added.

### 3.d.ii
Conditions for user input manages the garbage within our program. THese conditions are enforced by the placeholders. These make sure user input match the requested structure so that no false input goes in. Another way garbage is managed is through the second last command. It enforces that there is something to call back to.