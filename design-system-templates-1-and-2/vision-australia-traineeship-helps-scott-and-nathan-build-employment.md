# VISION-AUSTRALIA-TRAINEESHIP-HELPS-SCOTT-AND-NATHAN-BUILD-EMPLOYMENT
## WCAG compliance related to 2.1 AA
* The blockquote is not aplied using the `<blockquote>` element
* The visible table caption does not use the `<caption>` element and is not applied as a child element of the `<table>` element
* **Skip to main content** link does not work
* The **Share this video** dialog is not applying ARIA attributes correctly. Keyboard behaviour is not constrained with the dialog
* Table cell navigation arrows do not have link text
* The **Top** link is a clickable heading element, replace with a link element
* The Accordion is not applying ARIA attributes correctly. The `aria-expanded` attribute must be toggled from `true` to `false`
## Highly recommended usability suggestions for screen reader users
* Heading elements are applied out of sequence
* Reduce the word count in headings, as an example **Navigation card heading which runs across two or three lines** is a long heading
* Individual Word and PDF document links do not provide sufficient text to be understood on their own outside of the container i.e. _Word (9 KB)_
## Future proofing type suggestions
* Replace `<div role="navigation">` in the footer with a `<nav>` element
* Place the breadcrumb links within a `<nav>` element
* Provide multiple `<nav>` elements with an aria-label attribute and a unique name for each navigation region

## Screen reader testing
Navigation of page elements via keyboard commands was applied using JAWS v2021 and NVDA v2020.
* <kbd>Tab</kbd>, <kbd>Space</kbd> and <kbd>Enter</kbd> used to navigate interactive elements
* Links or elements list within NVDA and JAWS used to understand link text
* Navigation via headings
* Navigation via lists
### Recorded behaviour

