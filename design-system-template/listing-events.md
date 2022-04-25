# LISTING EVENTS
## WCAG compliance related to 2.1 AA
- Keyword search input contorl has no accessible name
- Date format contraint for **Min**, **Max** is not provided programmatically
- **Displaying 1 - 9 of 51** uses the style `view-header` but does not use header elements
- Links within the body content change colour only when in keyboard focus
- **Topic**, **Applies to**, **Keyword**, **Date Range** not visible when zoomed to 400%
- **Audio Described** tag does not reflow, text content on the cards is obscured when WCAG 2.1 AA text spacing requirements are applied
-  **Min**, **Max** datepicker control is not keyboard accessible
-  Phone number link has `aria-label="phone no"`

## Highly recommended usability suggestions for screen reader users
- None
## Future proofing type suggestions
- Typo **Short by** when zoomed to 400%
- Irregular heading levels applied, `<h3>` on the cards with no preceeding `<h2>`
- Insufficient and verbose page title
- Consider rephrasing the pagination links with the number followed by the ordinal indicator then text _2nd page_, _3rd page_
- Consider applying the `<time>` elements when displaying dates
- Consider wrapping each card element within a `<li>` element
- Consider using an aria-live region with `role="status"` to output when a page has re-sorted

## Screen reader testing
- Form control navigation using the keys <kbd>F</kbd>, <kbd>B</kbd>, <kbd>X</kbd>, (<kbd>R</kbd> NVDA only)

### Legend
- :heavy_check_mark: = Element exists and is applied correctly
- :x: = Element exists and is not working correctly
- :heavy_minus_sign: = Element does not exist
- :grey_question:= Unclear screen reader behaviour
- :white_circle: = Test not run

|   |Screen Reader   | Images | Headings  |Landmarks   |Tables   | Lists |Links |Form Controls | Sort & Filter | Pagination |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v100</sup> 		| JAWS <sup>v2021</sup> 	| :heavy_minus_sign:  | :x:  | :heavy_check_mark:  | :heavy_minus_sign: | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark: |
| Chrome <sup>v100</sup> 	| JAWS <sup>v2021</sup>  	| :heavy_minus_sign:  | :x:  | :heavy_check_mark:  |:heavy_minus_sign: |:heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark: |
| FireFox <sup>v99</sup> 	| JAWS <sup>v2021</sup>   	| :heavy_minus_sign:  | :x:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Edge <sup>v100</sup> 		| NVDA <sup>v2020</sup> 	| :heavy_minus_sign:  | :x:  | :heavy_check_mark:  | :heavy_minus_sign: | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark: |
| Chrome <sup>v100</sup> 	| NVDA <sup>v2020</sup>  	| :heavy_minus_sign:  | :x:  | :heavy_check_mark: | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| FireFox <sup>v99</sup> 	| NVDA <sup>v2020</sup>   	| :heavy_minus_sign:  | :x:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark: |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :heavy_minus_sign:  | :heavy_check_mark:  | :grey_question:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark: |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				| :heavy_minus_sign:  |:heavy_check_mark: | :grey_question:  | :heavy_minus_sign:  |:heavy_check_mark: | :heavy_check_mark:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  |
| Android <sup>v11</sup> 	| TalkBack 					| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle: | :white_circle: |

### Observations
|  | Element  | Notes |
|---|:-:|---|
| All combinations | Headings  | All `<h3>` card heading elements not navigable  |
| All combinations | Form Controls | When **Sort By**, **Topic**, **Location**, **When** are collapsed checkbox and radio buttons are not identified  |
| iOS | Links | Individual card elements are focusable using rotor link navigation |
|All combinations| Sort By |Last focus position is lost when **least recent** is selected
|All combinations| Sort By |Control collapses and last focus position is lost when **most recent** is selected
|Chrome, Edge, FireFox JAWS | Topic |Last focus position is lost when **Community Work** is selected
|All combinations | Topic |Control collapses and last focus position is lost when **Community Work** is selected
|Chrome, Edge, FireFox JAWS | Location |Last focus position is lost when **NSW** is selected
|All combinations | Location |Control collapses and last focus position is lost when **NSW** is selected
|Chrome, Edge, FireFox JAWS | When |Last focus position is lost when **This week** is selected
|All combinations | When |Control collapses and last focus position is lost when **This week** is toggled
|MacOS | Lists | Elipsis ignored and described on the pagination control links 
|iOS | Pagination | Last focus position is lost when **2** is selected
