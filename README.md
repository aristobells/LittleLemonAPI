# LittleLemonAPI

Fully functioning API project for the Little Lemon restaurant so that the client application developers can use the APIs to develop web and mobile applications. People with different roles will be able to browse, add and edit menu items, place orders, browse orders, assign delivery crew to orders and finally deliver the orders.

Capabilities:
The admin can assign users to the manager group
You can access the manager group with an admin token
The admin can add menu items
The admin can add categories
Managers can log in
Managers can update the item of the day
Managers can assign users to the delivery crew
Managers can assign orders to the delivery crew
The delivery crew can access orders assigned to them
The delivery crew can update an order as delivered
Customers can register
Customers can log in using their username and password and get access tokens
Customers can browse all categories
Customers can browse all the menu items at once
Customers can browse menu items by category
Customers can paginate menu items
Customers can sort menu items by price
Customers can add menu items to the cart
Customers can access previously added items in the cart
Customers can place orders
Customers can browse their own orders
API Endpoints:

---User Registration and Token Generation Endpoints:

• /api/users
• /api/users/users/me/
• /token/login/
---Menu Item Endpoints:

• /api/menu-item
• /api/menu-item
• /api/menu-item/{menuItem}
• /api/menu-item/{menuItem}
• /api/menu-item
• /api/menu-item
• /api/menu-item/{menuItem}
• /api/menu-item/{menuItem}
• /api/menu-item/{menuItem}

---User group management endpoints:

• /api/groups/manager/users
• /api/groups/manager/users
• /api/groups/manager/users/{userId}
• /api/groups/delivery-crew/users
• /api/groups/delivery-crew/users
• /api/groups/delivery-crew/users/{userId}

---Cart management endpoints:

• /api/cart/menu-items
• /api/cart/menu-items
• /api/cart/menu-items

---Order management endpoints:

• /api/orders
• /api/orders
• /api/orders/{orderId}
• /api/orders
• /api/orders/{orderId}
• /api/orders/{orderId}
• /api/orders
• /api/orders/{orderId}
