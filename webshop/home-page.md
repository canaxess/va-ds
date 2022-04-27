# Home Page
## WCAG compliance related to 2.1 AA
- **First name, Last name, Email** do not use the `autocomplete` attribute for user edittable inputs on **Let's keep in touch!**
- the cart icon and the letter 'C' (Cart) are obscured when the text spacing bookmarklet is applied
- **Introducing the Ucello Kettle** is marked up as a heading after the initial heading **Product heading** except no new content is shown
- every card beneath **Our wide range of products** is a heading element except no new content is shown
## Highly recommended usability suggestions for screen reader users
- none
## Future proofing type suggestions
- none
## Previous observed behaviour
- Cards have been marked up with `role="button"`, which won't allow screen readers to access to semantic information, eg, headings, lists etc within the button. This no longer applies.
