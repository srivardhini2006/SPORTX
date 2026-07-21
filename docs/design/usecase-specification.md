# Customer Use Cases

UC-001 Register

Description:
The customer creates a new account.

Actor:
Customer

Precondition:
User is not registered.

Postcondition:
A new account is created successfully.

--------------------------------------------------

UC-002 Login

Description:
The customer logs into the application.

Actor:
Customer

Precondition:
Customer has a registered account.

Postcondition:
Customer is authenticated.

--------------------------------------------------

UC-003 Browse Products

Description:
The customer views available sports products.

Actor:
Customer

Precondition:
Products exist in the database.

Postcondition:
Products are displayed.

--------------------------------------------------

UC-004 Search Products

Description:
Customer searches products using keywords.

Actor:
Customer

Precondition:
Products exist.

Postcondition:
Matching products are displayed.

--------------------------------------------------

UC-005 View Product Details

Description:
Customer views complete information about a product.

Actor:
Customer

Precondition:
Product exists.

Postcondition:
Product details are displayed.

--------------------------------------------------

UC-006 Add Product to Cart

Description:
Customer adds a product to the shopping cart.

Actor:
Customer

Precondition:
Product is available.

Postcondition:
Cart is updated.

--------------------------------------------------

UC-007 Update Shopping Cart

Description:
Customer changes product quantity.

Actor:
Customer

Postcondition:
Cart is updated.

--------------------------------------------------

UC-008 Remove Product from Cart

Description:
Customer removes a product from the cart.

Actor:
Customer

Postcondition:
Product removed.

--------------------------------------------------

UC-009 Checkout

Description:
Customer places an order.

Actor:
Customer

Precondition:
Cart contains products.

Postcondition:
Order is created.

--------------------------------------------------

UC-010 View Order History

Description:
Customer views previous orders.

Actor:
Customer

Postcondition:
Order history displayed.

--------------------------------------------------

UC-011 Update Profile

Description:
Customer updates personal information.

Actor:
Customer

Postcondition:
Profile updated.

# Administrator Use Cases

UC-012 Admin Login

Description:
Administrator logs into the system.

--------------------------------------------------

UC-013 Manage Products

Description:
Create, update and delete products.

--------------------------------------------------

UC-014 Manage Categories

Description:
Create, update and delete categories.

--------------------------------------------------

UC-015 Manage Inventory

Description:
Update product stock.

--------------------------------------------------

UC-016 Manage Orders

Description:
View and process customer orders.
