======================================
Restaurant Menu App as Item Catalog
======================================

Restaurant Menu App is a simple Python app that implements Item Catalog concepts.
It allowes users to read, created, delete, and update Restaurants and Menu Items.
It also provides API endpoints to access application data in JSON format. 
Web site provides third party authentication and authorization using Google and Facebook APIs.


Quick start
-----------

1. From command prompt start vagrant vitrual machine by using 'vagrant up' command.
	
2. From command prompt start vagrant shell using 'vagrant ssh' command.
	
1. Run 'python database_setup.py' command to create the restaurantmenuwithusers database.

2. Run 'python lotsofmenus.py' to populate the application database with sample restaurants and menu items.

3. Run 'python project.py' to start the Restaurant Menu App.

4. In your browser navigate to localhost:5000 to view the main page of Restaurant Menu App.

5. From the main page you will be able to login in using Google or Facebook user id and password, by clicking on the 'Click Here to Login' link.

6. To log out click the 'Disconnect' link.

7. Once logged in you will be able to Create, Delete, and Edit restaurants and menu items.

8. If you choose not to log in, you will be able to view restaurants and menu items, but will not be authorized to create, edit or delete.

9. To access API enpoints navigate to the following urls:

	localhost:5000/restaurant/JSON
		- to get information regarding all restaurants
	localhost:5000/restaurant/<int:restaurant_id>/menu/JSON
		-to get specific restaurant's menu items
	localhost:5000/restaurant/<int:restaurant_id>/menu/<int:menu_id>/JSON
		-to get specific menu item's details


