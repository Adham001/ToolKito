# ToolKito
Minimal E-commerce Android Application
===================

Android simple e-commerce application feel free to use it in your projects.

| [Tutorial](https://www.facecode.com)  |  [Google Play](https://play.google.com/) | [Video Demo](https://www.youtube.com/channel/UCOXi18i2MtkucVo_y2VwVGA/videos)|
|----------|--------|------|

![ToolKito](https://zupimages.net/up/20/07/a66j.gif)


ToolKito E-Commerce APP
===================
The example app I have created is very minimal with very limited screens. 

**Login, Register** - screens to login or create a new user.

**Home** – To list down the available products along with name, thumbnail and price.

**Cart** – A BottomSheet view to maintain the cart items.

**Payment** – screen To make the necessary calls to backend server before redirecting user to payment gateway.

**Transactions** – To show the list of transactions made by a user.


Java package
===================

```gradle
+ -- com.facecode.toolkito // parent package
+ -- + activity    // All activity page located here
+ -- + adapter     // Adapter class for list or grid
+ -- + data        // Data dummy generator class
+ -- + fragment    // Fragment class for tab, viewpager
+ -- + helper      // Drag and wipe lisview class helper
+ -- + model       // Model class to represent object
+ -- + utils       // Snippets code and support method
+ -- + widget      // View divider decorator for list and grid
```
