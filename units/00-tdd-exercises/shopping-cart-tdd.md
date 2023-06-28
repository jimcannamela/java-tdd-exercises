# Shopping Cart

Build a library for a shopping cart application.  You do not need to build the whole application, just the methods to make the cart work. 

Acceptance Criteria...

1. Given that I visit the site, when I begin shopping, then I expect my cart to be empty.
1. Given I have an empty cart, when I add an Item, then I expect to see `totalPrice` reflect the sum of all the Items in my cart, times the quantities of each item.
1. Given I have an empty cart, when I add more than one of an item, then I expect `itemQuantities()` to show the number of items I have added.
1. Given I have an empty cart, when I add items, then I expect `itemizedList()` reflect the items I have added along with their price and quantity.
1. Given I have an empty cart, when I add more than one of an item, then I expect `totalPrice()` to reflect both the item price and quantity.
1. Given I have a cart with items that are not on sale, when I add items that are on sale, I expect `onSaleItems()` to include only the items on sale.

## Hints

- You will need a class or object to represent the cart.
- You will need a class or object to represent the line items in the cart.
- Stick to whole numbers, or integers for the item prices.

