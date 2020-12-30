# Android-Simple-Sales-Inventory-App-with-Gif_Demo
This app simulates a POS software tool that records details of transactions after every purchase while calculating the subtotal and balance after payment has been submitted.

# Edits in spacing 
![Design-Demo](https://user-images.githubusercontent.com/20470279/103328046-3fd37480-4a25-11eb-9a8f-b6f0f21d6cdc.gif)


 # DESIGN

•	Activity_main.xml is where you design the content and layout of the app. Activity_main.xml in Android mirrors the way CSS is used to design the content structure in HTML. 
•	The code written in Linear Layout is used to design the three main categories for user input. These categories consist of “Product Name”, “Price”, and “Quantity (Qty)”. 
•	The following code circled in red represents each category that was implemented with a text box.
•	Within each Linear Layout section, ‘TextView’ and ‘EditText’ are implemented accordingly. In this application, within the “TextView”, all ‘layout_width’ and ‘layout_hieght’ are structured the same. The only difference is the “TextView” portion because the labels of the name, background color, and font color in the columns are different from top to bottom sections in the app. 


![Blank_textRow-Demo](https://user-images.githubusercontent.com/20470279/103329115-54197080-4a29-11eb-8b27-5e1e3d11abbd.gif)


•	The portion of code circled in red from activity_main.xml in the demo corresponds with the display layout circled in red from the Android app emulator. The ‘EditText’ attribute is configured the same for all three rows, “Product Name”, “Price”, and “Qty”, which are located at the top half of this app. These are the blank text rows.


![navyBlue_textBox-Demo](https://user-images.githubusercontent.com/20470279/103329521-f9811400-4a2a-11eb-8067-9c843b350ed0.gif)


•	The portion of code circled in blue from activity_main.xml in the demo corresponds with the display of the layout circled in blue from the Android app emulator. The ‘EditText’ attribute is configured the same for the following categories located in the center section of this app. These are the navy-blue text boxes. The font color of the text is white.

![Table-Row-Demo](https://user-images.githubusercontent.com/20470279/103329587-4369fa00-4a2b-11eb-920c-ecbba02cd34c.gif)


•	The portion of code being highlighted in the demo from activity_main.xml corresponds with the display of the layout circled in green on the Android app emulator. The table below the ‘Add-button’ was designed to store details of each transaction in purchase history. The ‘Add’ button was designed and placed in the center of the app to  add items from each transaction. 

The table consists of the following columns: 

 	Product Name
 	Price
 	Qty
 	Total

The columns are used to store specific details of purchase history that could be printed during lookups for future reference in Inventory.  


 # FUNCTIONALITY
 # Edits in decimal format
![Functionality-Demo](https://user-images.githubusercontent.com/20470279/103328307-62b25880-4a26-11eb-8d18-766fd3c335ca.gif)


•	This app was designed to function as an POS system that tracks purchases over a period of time. 
•	The basic functions are as follows: 
•	Type in the name of the product you are buying. 
•       Next, enter the price of the product and the quantity of that product.
•	Click Add. The item is added to the table below.
•       Next type in amount you would like to pay for the item. The balance is automatically  calculated. 
•	Continue until all items have been purchased. Transaction is complete and the cycle continues.
