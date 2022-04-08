# VISION-AUSTRALIA-TRAINEESHIP-HELPS-SCOTT-AND-NATHAN-BUILD-EMPLOYMENT
## WCAG compliance related to 2.1 AA
* The blockquote is not aplied using the `<blockquote>` element
* The visible table caption does not use the `<caption>` element and is not applied as a child element of the `<table>` element
* **Skip to main content** link does not work
* The **Share this video** dialog is not applying ARIA attributes correctly. Keyboard behaviour is not constrained with the dialog
* Table cell navigation arrows do not have link text
* The **Top** link is a clickable heading element, replace with a link element
* The Accordion is not applying ARIA attributes correctly. The `aria-expanded` attribute must be toggled from `true` to `false`
*	Breadcrumbs container should be `<nav>` or `role="navigation"` with a label, eg. `aria-label="You are here"`
*	Responsive Menu content available to screen reader users when collapsed (should hide with `display: none`)
*	Main navigation items not keyboard accessible (`<a>` without `href` attribute). Also, remove all `tabindex` values greater than `0`

* Side navigation is correctly a list, but is nested inside an unnecessary single item list (whole list is list item 1 in parent list)
* "On this page" h5, should be h2
* Some main page headings are h4 instead of h2, where sub heading related to them are h3 (sometimes h4) - this may be only there to label the page components? May be worth having headings or screen reader headings to label these sections 
* Menu overlay in focus order (between header and breadcrumbs)
* No focus indicator on Back to news / side nav, or On this page links
* View in Google maps and Share this location icons are decorative but have alt text
* Map - can't scroll list of keyboard shortcuts with keyboard.
* Map - Location should be provided in text
* "text summary" on download item is marked up as a heading - should be regular text
* Download options should be marked up as a list`
* "Share this video" modal announced as "Share this location". Appears the heading in each modal shares the same ID, issue may also be cause by `aria-hidden="true"` when open.
* Responsive main menu accessibility link does not have link text (icon only)
* Responsive phone link has label "phone no"
* Download program item with image, image should be after heading (in code) or decorative.
* Accordion "+" implemented via CSS content - this causes mobile screen readers to stop on them as the user moves through - ideally wrap in a separate `<span>` with `aria-hidden="true"`

## Highly recommended usability suggestions for screen reader users
* Heading elements are applied out of sequence
* Individual Word and PDF document links do not provide sufficient text to be understood on their own outside of the container i.e. _Word (9 KB)_. Each link within each card should announce in the following order _'publication title (extracted from card header), file format, file size'_. e.g. **Your NDIS success planning guide PDF 1 point 5 megabytes**
* Reduce the word count in headings, as an example **Navigation card heading which runs across two or three lines** is a long heading
## Future proofing type suggestions
* Replace `<div role="navigation">` in the footer with a `<nav>` element
* Place the breadcrumb links within a `<nav>` element
* Provide multiple `<nav>` elements with an aria-label attribute and a unique name for each navigation region

*	Don't automatically close accordions when another is opened
*	Task cards, tables and embedded map all h4, which nests them under the previous sections subheading (navigation card item heading, "Register for a workshop", etc which are h3)
*	Next steps links have headings so there must always be content. If these will never have much text content, I'd suggest removing the heading as it's more like just a link. Any items with headings that remove the content for mobile should remove the heading markup on mobile.
*	Remove hidden heading in Menu that is non descriptive "new_navigation"


## Screen reader testing
Navigation of page elements via keyboard commands was applied using JAWS v2021 and NVDA v2020.
* <kbd>Tab</kbd>, <kbd>Space</kbd> and <kbd>Enter</kbd> used to navigate interactive elements
* Links or elements list within NVDA and JAWS used to understand link text
* Navigation via headings
* Navigation via lists
### Recorded behaviour
- <kbd>Tab</kbd> key becomes stuck when reaching side navigation and won't progress any further
- Cannot open side menu
- Navigating via list elements focus moves to hidden side navigation items
- Several unclear file format links i.e. _PDF (7.74 KB)_
- Unclear table cell right arrow link text
- Cannot reach any of the top menu links _Menu, Search, Display, Telephone, Donate now_
- Accordion expand/collapsed behaviour is not audibly described
### Additional notes
- iOS VoiceOver seemed to skip over lots of content - unclear why.
- When screen readers interact with the table, the screen scrolls up to the top of the page - some sighted users use screen readers so that may be an issue
- It's possible native mobile screen reader table controls may not work for tables the way they are implemented on mobile - worth having some experienced VoiceOver or Talkback users give these pages a try

