# Screen reader scenarios
Navigation of page elements via keyboard commands was applied using:

- Chrome v100, Edge v100, FireFox v99 and JAWS v2021
- Chrome v100, Edge v100, FireFox v99 and NVDA v2020

## Adding a product to wishlist **PASS**
- can skip repeating page elements to move to the main content
- tabbing through the quantity buttons announces "die minus button" in JAWS only
- can find **Add to Wishlist**
- can action **Add to Wishlist**
- notified item is added to wishlist (except FireFox & JAWS)
## Purchasing a product as a logged in user **PASS**
- can find "Add to Cart"
- have to reorientate myself to the top of the screen to navigate to the Cart via the top right link
- navigating via the links/elements list cart link text displays "Cart 1 1 items"
- can review my order
- all forms controls for address and adding a new credit card are clearly labelled
- can identify and action **Make Payment**
- payment is processed
- redirected to order received page

<br>note. general difficulty navigating with FireFox and JAWS
## Purchasing a product as a guest **FAIL**
- all controls are clearly labelled
- address autosuggest does not announce returned results
- selecting **Billing address same as shipping address** focus moves to **Click and Collect**
- can not action **Make payment** (except Chrome and JAWS, FireFox and NVDA)
## Purchasing a gift card
- cannot skip repeating content via skip links
- all input controls are unlabelled
- spin box outputs "To set the value use the arrow keys or type the value" which I could guess was the value field
- good valdiation summary except it unclear what's in error due to unlabelled controls
- can not complete
