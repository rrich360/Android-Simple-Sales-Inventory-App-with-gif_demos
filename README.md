# Android-Simple-Sales-Inventory-App-with-Gif_Demo
This app simulates a POS software tool that records details of transactions after every purchase while calculating the subtotal and balance after payment has been submitted.

[1]()

 # DESIGN

•	Activity_main.xml is where you design the content and layout of the app. Activity_main.xml in Android mirrors the way CSS is used to design the content structure in HTML. 
•	The code written in Linear Layout is used to design the three main categories for user input. These categories consist of “Product Name”, “Price”, and “Quantity (Qty)”. 
•	The following code circled in red represents each category that was implemented with a text box.
•	Within each Linear Layout section, ‘TextView’ and ‘EditText’ are implemented accordingly. In this application, within the “TextView”, all ‘layout_width’ and ‘layout_hieght’ are structured the same. The only difference is the “TextView” portion because the labels of the name, background color, and font color in the columns are different from top to bottom sections in the app. 

[2]()

•	The portion of code circled in red from activity_main.xml in the demo corresponds with the display layout circled in red from the Android app emulator. The ‘EditText’ attribute is configured the same for all three rows, “Product Name”, “Price”, and “Qty”, which are located at the top half of this app. These are the blank text rows.

[3]()

•	The portion of code circled in blue from activity_main.xml in the demo corresponds with the display of the layout circled in blue from the Android app emulator. The ‘EditText’ attribute is configured the same for the following categories located in the center section of this app. These are the navy-blue text boxes. The text font color is white.

[4]()

•	The portion of code being highlighted in the demo from activity_main.xml corresponds with the display of the layout circled in green on the Android app emulator. The table below the ‘Add-button’ was designed to store details of each transaction in purchase history. The ‘Add’ button was designed and placed in the center of the app to  add items from each transaction. 

The table consists of the following columns: 

 	Product Name
 	Price
 	Qty
 	Total

The columns are used to store specific details of purchase history that could be printed during lookups for future reference in Inventory.  


 # FUNCTIONALITY
					[5]()

•	This app has ability to take in input for tracking purchases via calculating Balance after amount of payment has been submitted then storing details of the purchase in the table below the add button.
•	Type in the name of the product you are buying. Next, enter the price of the product and the amount of that product for quantity.
•	Click Add. The item is stored. Next type in amount you would like to pay for item. The balance is automatically updated. 
•	Continue until all items have been purchased.
