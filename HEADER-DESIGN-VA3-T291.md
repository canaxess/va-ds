## Header Design
### WCAG compliance related to 2.1 AA
* replace the `<p>` element with a `<button>` element on the open menu (`<p class="ammenu-menu-header" aria-label="Close Menu" data-bind="`)
* remove `tabindex=0` from the span element on the open menu (`class="ammenu-message"`) 
* add a unique ID e.g. `id="sidenavigation"` to the side navigation on the open menu (`<nav data-action="navigation"`)
* confirm `aria-expanded="false"` correctly changes to true when the menu is open, and false when the menu is closed (`<button aria-expanded="true" role="button" id="toggle_button"`)
* Main logo/link should have alt text “Home – Vision Australia store – logo” or along those lines.
*	Phone icon should have alt text (sr-only text for screen readers, “Phone:” or “Call”, etc.

Status : **complete**

## Menu
### WCAG compliance related to 2.1 AA
* Keyboard focus can escape the menu when it is open by going backwards (<kbd>Shift</kbd> + <kbd>Tab</kbd>), which shouldn’t happen
* <kbd>ESC</kbd> key should dismiss the menu and return focus to the Menu button
* Category submenus should be marked up as lists
* Non-expandable links should not have aria-expanded
* Link to VA website at end of menu needs sr-only text to say it opens in a new window, as the icon provides this information visually.
* when menu is open close button has focus
* close button currently doesn't work via the keyboard 

### Future proofing suggestion
* add `aria-controls="sidenavigation"` to the menu button which opens the menu (`<button aria-expanded="true" role="button" id="toggle_button"`)

Status : **incomplete**

## Search link
### WCAG compliance related to 2.1 AA
* replace the search link (`class="searchicon" aria-label="search products"`) with a button element
* replace the `<i>` element for scaffolding icons with the `<span>` element
* when search is open focus is on the search input control (search entire store here)
* keyboard focus cycles through the back arrow, search control and magnifying glass icon only
* make the back arrow into a button element
* when closed return focus to the search button
* back arrow/button should not be inside the `<label>` of the field
* <kbd>ESC</kbd> should return user to the search button
*	Placeholder text should be at least 4.5:1 colour contrast against the background of the field
*	Focus indicator for Search button? And for all interactive items in the panel when they are present.

### Highly recommended usability suggestions 
* it would be nice for screen reader users if they were provided that information that is on screen to avoid them having to load the search page to find there are no results
* this feature could cause some confusion for people with cognitive disabilities, the way it takes over the whole screen with just a white background. It may appear to some that they have left the website or closed it somehow

Status : **incomplete**

## User dropdown
### WCAG compliance related to 2.1 AA
* replace the link (`minilogin-toggle`) with a button element
* add `aria-label="open login menu"` to the button element (`minilogin-toggle`)
* add the attribute `aria-expanded` and toggle between values `"true"` and `"false"` when the dropdown is shown and hidden
* add the attribute `aria-controls="minilogin-content-wrapper"`
* when login menu is visible move focus to first menu item (My Account)
* pressing tab and <kbd>Shift</kbd> + <kbd>Tab</kbd> cycles the focus through Hi Sande..., My Account, My Wishlist, Logout only
* when the button (`minilogin-toggle`) is expanded change the `aria-label` text to `"close login menu"`

Status : **incomplete**

## Questions
Q. can the items be focusable via a left-to-right sequence? Menu, Search, Vision Australia, Telephone number, Login, Cart?<br>
A. the current sequence is suggested by the SR

Q. remove `tabindex=0` from the span element on the open menu (`class="ammenu-message"`)<br>
A. can we keep this to make the tab movement inside the menu popup
