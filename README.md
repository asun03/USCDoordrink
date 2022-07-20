# USCDoorDrink

USC DoorDrink
Team #42
Authors: Angela Sun, Tiffany Chen, Madison Brading

Note: alternate working repo can be found at https://github.com/tchen874/USCDoorDrink

USCDoorDrink is a drink delivery app created by and for USC students.

Store owners are able to create their stores and add their drink menus accordingly. They are also able to view their order history and current orders.

Users are able to find nearby coffee stores using a map and place their orders. They can see different delivery routes and estimated delivery times, as well as their order history and current orders.

# EMULATOR INSTRUCTIONS:
Use Pixel 3a API 32 on Android Studio

# Run Instructions
Run the app. This takes you to the login screen.
if you do not have an account, click "No Account?". This will prompt you to create an account.
If you already have an account, log in.
If you've forgotten your password, click "Forgot Password?". This prompts you to enter your email, and sends an email to that email address to reset the password.
Click outside the keyboard or the down arrow in the lower left corner to lower the keyboard if necessary.

After logging in, the merchant and user views are different.

## Merchant View:
The home page is a map displaying the merchant's current location and nearby stores. The hamburger menu in the upper left corner displays the following options:
### View map
View Map takes the user to a map view populated with markers of stores. Click the target button on the upper right to go to your current location.
If necessary, there are zoom in and zoom out controls on the lower right.
Merchant addresses in the database are automatically set as markers to the map.
Clicking the marker lets the user view the store's name, address, phone number, and menu.

### edit menu
This page enables merchants to add, update, and delete their menu items.
To add a drink, press the add button and enter the drink name, price, and caffeine levels. Then press enter.
To delete a drink, press the x button next to the drink on the right.

### order history
The merchant is able to see their customer order history in both list and chart form by day, month, and year.

### profile
This button takes the user to their profile.
For merchants, profile is where their information such as name, address, and phone number are set.
To have their store location appear as a marker on the map, enter the store address and press update.

### Logout
This option logs the user out.


## User View:
below is for the user view

### View Map
View Map takes the user to a map view. Click the target button on the upper right to go to your current location.

If necessary, there are zoom in and zoom out controls on the lower right.
Merchant addresses in the database are automatically set as markers to the map.
Clicking the marker once allows the user to view a route from their current location to the store. They are able to choose different modes of transportation and the necessary travel time and distance to reach the store.
Clicking the marker again lets the user view the store's name, address, phone number, and menu. The menu can be sorted by best match, price, and caffeine.
From there, the user can add drinks to their cart.
If their caffeine levels exceed the recommended daily amount, the user will get an alert.
The user can then check out the cart and place their order.


### Order History
This takes the user to a view of their order history.
The user is able to see the current weather. Depending on the temperature, they are recommended a drink to order.
The user is able to see their order history in both list and chart form.


### About us
This takes the user to an 'about us' page detailing information about the app and its creators :)


### Profile
This button takes the user to their profile.
Users will be able to see and edit their name, email and phone number.


### Logout
this button logs the user out.

### new updates
- Implementation of features such as showing biking and driving route + times from current location to store
- UI changes such as showing category names before the editText
- Added toasts to notify user an action has been completed after adding to cart, checking out, etc
- Additional features such as:
  - User can filter menu items from best match, price low-to-high, price high-to-low, caffeine high-to-low and caffeine low-to-high
  - User gets drink recommendation based on the weather of their current location with multiple different scenarios possible depending on whether weather is less than 40 degrees fahrenheit, between 40 and 72 degrees fahrenheit, between 72 and 85 degrees fahrenheit, and above 85 degrees fahrenheit.
  - User can check out a comprehensive view of their order history through swiping between tabs and then seeing a graphical representation of their order history
  - Merchant can check out a comprehensive view of their order history through swiping between tabs and then seeing a graphical representation of their customer order history



