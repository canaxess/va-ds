# Header Design
* replace the `<p>` element with a `<button>` element on the open menu (`<p class="ammenu-menu-header" aria-label="Close Menu" data-bind="`)
* remove `tabindex=0` from the span element on the open menu (`class="ammenu-message"`) 
* add a unique ID e.g. `id="sidenavigation"` to the side navigation on the open menu (`<nav data-action="navigation"`)
* add `aria-controls="sidenavigation"` to the menu button which opens the menu (`<button aria-expanded="true" role="button" id="toggle_button"`)
* confirm `aria-expanded="false"` correctly changes to true when the menu is open, and false when the menu is closed (`<button aria-expanded="true" role="button" id="toggle_button"`)

Status : **complete**

---

* when menu is open close button has focus
* close button currently doesn't work via the keyboard 

Status : **incomplete**

---

## Search link
* replace the search link (`class="searchicon" aria-label="search products"`) with a button element
* replace the `<i>` element for scaffolding icons with the `<span>` element
* when search is open focus is on the search input control (search entire store here)
* keyboard focus cycles through the back arrow, search control and magnifying glass icon only
* make the back arrow into a button element
* when closed return focus to the search button

Status : **incomplete**

---

## User dropdown
* replace the link (`minilogin-toggle`) with a button element
* add `aria-label="open login menu"` to the button element (`minilogin-toggle`)
* add the attribute `aria-expanded` and toggle between values `"true"` and `"false"` when the dropdown is shown and hidden
* add the attribute `aria-controls="minilogin-content-wrapper"`
* when login menu is visible move focus to first menu item (My Account)
* pressing tab and <kbd>shift</kbd> + <kbd>tab</kbd> cycles the focus through Hi Sande..., My Account, My Wishlist, Logout only
* when the button (`minilogin-toggle`) is expanded change the `aria-label` text to `"close login menu"`

Status : **incomplete**

---
## Questions
Q. can the items be focusable via a left-to-right sequence? Menu, Search, Vision Australia, Telephone number, Login, Cart?<br>
A. the current sequence is suggested by the SR

Q. remove `tabindex=0` from the span element on the open menu (`class="ammenu-message"`)<br>
A. can we keep this to make the tab movement inside the menu popup
