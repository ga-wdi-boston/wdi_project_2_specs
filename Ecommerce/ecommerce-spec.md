# E-Commerce

## Outline
Famed Boston bagel restaurant "Bob's Bagels" needs a new website with a full menu and an online order system for ordering either (1) bulk bagels, or (2) customizable bagel sandwiches (to which toppings can be added or removed, affecting the price of the sandwich).

## Assets (provided to students):
- name (“Bob’s Bagels”)
- menu, with prices (menu.txt)
- delivery information (delivery.txt)
- bio for Bob (bio.txt)

## Must-Have Features:
- menu must be visible on the site
- Bob’s bio must be somewhere on the site
- users can place orders and are billed appropriately (including delivery charges)
- users can see an order history
- users can view an order in progress and change the order before placing it
- users can customize sandwiches by adding items (increasing the price) or removing items (not affecting the price)
- users can pay by credit card (via the Stripe API)

## Nice-to-Have Features:
- site should be fully mobile-friendly
- users can enter promotional discount codes for their orders
- two different user paths for buying single sandwiches vs. bulk catering
- rotating weekly specials
- multiple people can contribute to the order
- orders can be saved for future use

Note: Building a good shopping cart that is intuitive to use is harder than it seems. Consider that buying an item is a multi-step process, from browsing the choices, to making a selection, to modifying the quantity of your order, to paying (with possible confirmation of your order before and after you pay). Users may want to change their order at any point during this process.
