# FoodNest Ordering App

This project was created using React Native with MaterialUI for UI/UX. This project also includes a mock backend server which was created using JSON Server to simulate calls to a server.

## Available functions

This app involves both customer and admin view. Users can switch between these two views using the toggle button at the bottom of the page.

### Customers

Customers using the app will be able to: 
1. Add items to cart.
2. View cart. Cart state is saved using localStorage, so feel free to refresh.
3. Increase item quantity.
4. Decrease item quantity.
5. Remove item to cart by reducing item quantity to 0.
6. Place orders. (Orders are sent to mock backend)

### Admin

Admins are able to:
1. Add items to the menu.
2. Remove items from the menu. 
3. Edit items in the menu.
4. View orders.
5. Delete orders.
