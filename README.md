# Grocery-List

- For this assignment, 
I have used:

1) AngularJS for front-end. 
2) NodeJS,ExpressJS for back-end. 
3) MySQL as the database communicator. 

The application once succesfully connected to the database will, 

1) Allow to create a new grocery list item by clicking on the 'Add a new Item' button . The 'Submit' button in the form ensures that it is disabled if the item title is not entered by the user. It enables once there is a new title. The item description textbox is an optional field.
2) The user can view the displayed item title alongside a checkbox that can be checked to mark an item as 'complete'. 
3) The user can 'unpurchase' an item once it has been marked complete. This functionality is available by clicking on the 'View All Completed Items' button. This will open a list of all completed items. Simply hit 'Un-Purchase' to put the item back on the active list. 
4) The user can delete the item, removing the item from the database by clicking on the 'Delete' button. 
5) The user can view/modify the item title or the item description by clicking on the 'View/Modify' button. 


Instructions for usage. 

1) Run command: 

nodemon

This will start the server. 

2) db.config.js contains the credentials for connecting to the database. Please modify these credentials to run the database on your end.

3) All files are in Grocery List.zip.
