# E-Commerce

## Outline
Famed Boston bagel restaurant "Bob's Bagels" needs a new website with a full menu and an online order system for ordering either (1) bulk bagels, or (2) customizable bagel sandwiches (to which toppings can be added or removed, affecting the price of the sandwich).

## Assets (provided to students)
- name (“Bob’s Bagels”)
- menu, with prices (see below)
- delivery information (see below)
- bio for Bob (see below)

## Must-Have Features
- menu must be visible on the site
- Bob’s bio must be somewhere on the site
- users can place orders and are billed appropriately (including delivery charges)
- users can see an order history
- users can view an order in progress and change the order before placing it
- users can customize sandwiches by adding items (increasing the price) or removing items (not affecting the price)
- users can pay by credit card (via the Stripe API)

## Nice-to-Have Features
- site should be fully mobile-friendly
- users can enter promotional discount codes for their orders
- two different user paths for buying single sandwiches vs. bulk catering
- rotating weekly specials
- multiple people can contribute to the order
- orders can be saved for future use

Note: Building a good shopping cart that is intuitive to use is harder than it seems. Consider that buying an item is a multi-step process, from browsing the choices, to making a selection, to modifying the quantity of your order, to paying (with possible confirmation of your order before and after you pay). Users may want to change their order at any point during this process. Ideally, users don't have to log in to pay, but can choose to create an account and/or log in at any point and continue their order exactly where they left off.

## Assets

### Bob's Bio

Robert "Bob" Bagler was born in Boston in 1951; after years of working in his father's restaurant, "Arthur's", he struck out on his own in 1979 and started Bob's Bagels right where it sits today, at XYZ Ave in Boston. For the last forty years, Bob's Bagels has strived to proved the best bagels in town, at the best prices, made with love from only the freshest ingredients. Bob still works the counter, just like the old days, so stop in sometime and say hello!

### Delivery

Customers must enter their address if they want delivery. Charges are:  
  + $6.00 if in downtown Boston, South Boston, or the North or South End  
  + $10.00 if in Brookline, Allston, Cambridge, or Somerville  
Currently no delivery to anywhere else.  

### Menu

Catering Menu 
  - Small bagel box (12 bagels)    
      -> plain bagels : $12    
      -> variety bagels : $15    
        * 2 each of : plain, sesame seed, poppy seed, onion, whole wheat, cinnamon raisin  
      -> single-variety box : $15    
        * 12 of any one variety (see list above)  
  - Large bagel box (18 bagels)    
      -> plain bagels : $18    
      -> variety bagels : $20    
        * 3 each of : plain, sesame seed, poppy seed, onion, whole wheat, cinnamon raisin  
      -> single-variety box : $20    
        * 18 of any one variety (see list above)  
  - Cream Cheese (catering size)    
      -> plain : $4.00  
      -> chive : $4.50  
      -> tofutti (vegetarian) : $4.50  
      -> salmon spread : $5.50  
  - Party Box (25 bagels plus plain and chive cream cheese) : $50  

Sandwiches  
  - The Somerville : $6.75  
      whole wheat bagel with  
          - avocado  
          - tomato  
          - cucumber  
          - sprouts  
          - tofutti cream cheese  
  - The North End : $6.50  
      onion bagel with  
          - roast beef  
          - tomato  
          - red onions  
          - asiago cheese  
          - provolone cheese  
  - The South End : $6.50  
      sesame bagel with  
          - corn beef  
          - cole slaw  
          - swiss cheese  
          - spicy mustard  
  - The Hub : $6.00  
      plain bagel with  
          - turkey  
          - garlic mayonaisse  
          - tomato  
          - cucumber  
          - sprouts  
  - The Brookline : $7.50  
      poppyseed bagel with  
          - cream cheese  
          - tomato  
          - red onions  
          - smoked salmon  
  - Build Your Own!  
      Options  
        plain bagel : $2.50  
        variety bagel (non-plain) : +$0.50  
        tomato / cucumber / red onions / cole slaw : free  
        mayo / garlic mayo / mustard / spicy mustard: +$0.50  
        cream cheese (plain or chive) : +$1.50  
        tofutti : +$2.00  
        salmon spread : +$2.50  
        asiago / provolone / swiss / cheddar cheese: +$0.50  
        avocado : +$2.00  
        sprouts : +$0.50  
        turkey : +$2.00  
        smoked salmon : +$3.50  
        roast beef : +$2.00  
        corn beef : +$3.00  

Beverages  
  Fountain soda  
    Small : $2.75  
    Large : $3.50  
  Hot Coffee  
    Small : $2.00  
    Large : $2.50  
  Latte  
    Small : $3.50  
    Large : $4.25  
