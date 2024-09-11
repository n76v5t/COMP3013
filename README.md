java cCOMP3013 Mobile Applications Development 
Spring 2024 
Assignment 1 
MenUWS 
Due: 8th
 September 2024 
(Students must demonstrate their assignments at the tutorial time in week 9). 
 
Assignment Details 
 
For this assignment, you are required to create a simple food ordering system as an Android App. 
The app Menulog should serve as a guide to how these sorts of apps typically work. It is suggested 
you download this app and experiment with it. There should be a login screen and options such as 
restaurants, food items and orders. The app should include a home screen that includes one or more 
decorative images and options as above (e.g. button, menu items, tabs etc.) The App has three main 
functions aside from the home screen: 
 
1. Allow user to view restaurants and their food items, typically this shows popular cuisines 
2. Allow user to create, view and modify orders from the restaurants and food items 
3. Provide an admin section where an admin user can login and create the restaurant and food items. 
 
In function 3 above, the creation of restaurant and food items is effectively an administrator only 
screen which would not normally be part of a user-only app. For the purposes of this assignment 
the details of the restaurants, food dishes and orders should be stored in a ‘database’, such as 
SQLite database. For a basic pass, list or file structure is acceptable. Please refer to the marking 
guide to for more details. 
 
In particular, the App should: 
 
Pass level (up to 64%): 
 
1. Provide the main interface and corresponding actions where user can select an option from 
buttons or other controls including 
o Add a new restaurant record. The information includes: Id (unique number for each item), 
name, style of food (eg. Thai, Chinese, Australian, Italian, etc), location, minimum order charge 
and image (image is optional, can be left blank). 
 
o Edit a restaurant record. The user can select a item from the list. The program will display all 
details of the restaurant in the corresponding fields where the information can be edited. The 
page should also include an option to delete the current record in addition to the edit option. 
 
o View restaurant records as a list in the main part of the app for ordering. 
 
2. As above for food/dish items. 
o Add a new food item. The item record includes details such as id, dish name, restaurant, 
main ingredients, price, and image (image is optional, can be left blank). o Edit a food record: the user can select an item from the list. The program will display all 
details of the item in the corresponding fields where the information can be edited. The page 
should also include an option to delete the current record in addition to the edit option. 
 
o View food records as a list in the main part of the app for ordering. 
 
3. Provide the main interface and implemented actions where the user can select an option from 
the buttons/menus for manipulating orders including 
o Make an order. The order record includes details such as order number (like id), restaurant, 
dishes, total price and address. For a pass, the order details can be manually entered by 
the user like restaurant name, dishes, address and the total price can be left empty. To gain 
more marks, the restaurant and dishes option should be queried from the database. See the 
descriptions in the higher grades section. 
 
o View the orders and confirm when finished to lodge the order. 
 
 - Be able to return to the home page or the previous page. 
- Provide an acceptable quality user interface - Are the screens easy to use? Are they laid out 
neatly? 
Do they look good? 
- For a pass it is not necessary to store data in an SQLite database. 
- It is not required to have scrolling or restoring of states such as list positions. 
- Images of restaurants and foods items are not required. 
- Code may not be well commented, named or well laid out. 
 
Higher grades eg. Credit level (up to 74%), Distinction (up to 84%), High Distinction: 
 
Include all required functions of the pass level, plus 
- Store at least one of restaurant or food or order data using an SQLite database 代 写COMP3013、C/C++，Python
代做程序编程语言5% 
- Use of multiple tables in SQLite  storing previous orders 3% 
- When making an order, the app provides the user the ability to select a restaurant from 
a list of restaurants then choose one or more dishes from the list of dishes available in 
the selected restaurant. The total price for the order is calculated accordingly and 
displayed on the form. 5% 
- Edit an order. The program will display all details of the item in the corresponding fields 
where the information can be edited. The page should also include an option to delete the 
current record in addition to the edit option. 4% 
- Login and logout facilities for customers and admins (usernames and passwords can be 
hardcoded). 3% 
- Bottom navigation app using fragments. 5% 
- Associate hardcoded images with food items (or restaurant) 3% OR 
- Taking of photos or use Gallery  associating them with food items (or restaurant) 5% 
- Good documentation, comments, naming, etc. 3% 
- Overall presentation, ease of use, good graphics 3% 
 
 Deliverable 
You are only allowed to use Android Studio to code your solution. Your program must be 
executable to pass. You are strongly advised to keep multiple versions in case of unforeseen 
problems. Last minute changes to programs often result in serious problems. You might modify 
the code from related source(s) with a proper citation(s) and you must be able to explain clearly 
your code. The external code should contribute less than 30% of the total program. No part of 
the code can be written by any other persons except as specified above. 
 
Declaration 
There is no requirement for documentation other than that in the code which should include your 
name and purpose of the code. However, you are required to submit a declaration with the 
following claim (in a text file or MS Word file). 
 
DECLARATION 
I hold a copy of this assignment that I can produce if the original is lost or damaged. 
 
I hereby certify that no part of this assignment/product has been copied from any other student’s 
work or from any other source except where due acknowledgement is made in the assignment. 
 
No part of this assignment/product has been written/produced for me by another person except 
where such collaboration has been authorised by the subject lecturer/tutor concerned. 
 
Submission 
Both the declaration and source code should be submitted via vUWS before the deadline for 
documentation/checking purposes. Source code only should be zipped into one file with your 
student id as the zipped file name. Use WinZip or WinRAR only. Submission that does not 
follow these formats is not acceptable. No hard copy of source code or email submission is 
acceptable unless by special arrangement with your tutor. 
 
Demonstration 
You are required to demonstrate your program during your scheduled practical session at the 
specified teaching week (or based on the advice of the lecturer/tutor). Your tutor will check your 
app and your understanding of the code. Make sure that you are fully familiar with the operation 
of your app and draw the tutor’s attention to any special or advanced features you have 
incorporated. You must have sample data in the app at the beginning of the demonstration. You 
will receive no marks if you miss the demonstration time without an application for special 
consideration. To prove that the program is written by yourself, the tutor might require you to 
make some minor modifications. In this case, you must complete what is required in order to 
prove that the code is only written by yourself. You are allowed to run your program from your 
laptop or Android device at the demonstration time. The majority of feedback to your work will 
be delivered orally during the demonstration. Final marks will be posted on vUWS after code 
checking of your on-line submission. 
 
The program you demonstrate should be the same as the one you submit. If you fail this 
assignment at your first demonstration, you are allowed to improve your work within one week 
(maximal grade is pass i.e. 50% in this case). Note that passing the assignment is not a 
requirement to pass the unit. 

         
加QQ：99515681  WX：codinghelp
