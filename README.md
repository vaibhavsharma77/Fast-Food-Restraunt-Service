
# Fast Food Resturant Service

This application is developed using builder desing pattern.

# Use Case

In Fast food Resturant,We normally order two types of Meals(considering burger as a meal in this use case) along with soft drink.
- Veg Burger 
- Non-Veg Burger 

Meals are packed inside a wrapper and drinks are served in bottle so we have consider packaging of meal and drinks also.

Builder Pattern will provider the option to server the request from main class (acting as a customer in this use case)











## Roadmap

- Creating an Item Interface consist of name of the item.packing and price info.

- Meal Class will consist of item list,add item info

- Burger will be abstract class (share the common functionality) for Veg Burger or Non Veg Burger .Burger will implement Item Interface.

- Packing will also be an interface contains info for type of packing.(wrapper or bottle)

- Meal Builder Class will provide different type of object for selecting different meal options.

- Soft Drink class can also be abstract class which will implement Item interface.(considering Cola or Pepsi in this use case)

