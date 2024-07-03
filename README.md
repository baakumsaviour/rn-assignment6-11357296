# rn-assignment6-11357296
# React Native Shopping App
This project is a React Native application that simulates a shopping experience. The app allows users to browse products, add items to their cart, view the cart, and proceed to checkout.

## Key Features
1. Home Screen: Displays a list of products.
2. Product Screen: Shows detailed information about a selected product.
3. Cart Screen: Allows users to view and manage items in their cart.
4. Checkout Screen: Displays a summary of the cart and allows users to proceed with the checkout.

# Design Choices
## UI Components
1. FlatList: Used for efficiently rendering lists of products and cart items.
2. Image: Used to display product images, icons, and logos.
3. TouchableOpacity: Used for interactive elements like buttons.
4. Text: Used for displaying textual information.
## Navigation
1. React Navigation: Used to navigate between different screens in the app.
Styling
2. StyleSheet: Used to create consistent and maintainable styles.
3. Flexbox: Used for responsive layout design.
## Data Storage
## AsyncStorage
1. Persisting Data: Used @react-native-async-storage/async-storage to save and retrieve cart data locally on the device.
2. State Management: Managed the state of cart items using useState and synchronized with AsyncStorage to ensure data persistence across app sessions.

# Screenshots
HomeScreen:
![HomeScreen](https://github.com/baakumsaviour/rn-assignment6-11357296/assets/143946622/5d2980d1-649a-4207-9def-bb8ef3aa9774)
CartScreen:
![Cart](https://github.com/baakumsaviour/rn-assignment6-11357296/assets/143946622/83ee44bd-70d7-43e0-8094-de148f3a18de)

