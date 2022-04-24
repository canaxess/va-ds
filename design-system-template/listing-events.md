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

|   |Screen Reader   | Images | Headings  |Landmarks   |Tables   | Lists |Links |Form Controls | Sort & Filter | Pagination |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v100</sup> 		| JAWS <sup>v2021</sup> 	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign: | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  | x | :heavy_check_mark: |
| Chrome <sup>v100</sup> 	| JAWS <sup>v2021</sup>  	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  |:heavy_minus_sign: |:heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  | x | :heavy_check_mark: |
| FireFox <sup>v99</sup> 	| JAWS <sup>v2021</sup>   	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark: | x | :heavy_check_mark: |
| Edge <sup>v100</sup> 		| NVDA <sup>v2020</sup> 	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign: | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark:  | x | :heavy_check_mark: |
| Chrome <sup>v100</sup> 	| NVDA <sup>v2020</sup>  	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark: | x | :heavy_check_mark: |
| FireFox <sup>v99</sup> 	| NVDA <sup>v2020</sup>   	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  | x | :heavy_check_mark: |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | x | x |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | x | x |
| Android <sup>v11</sup> 	| TalkBack 					| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | x | x |

### Observations
|  | Element  | Notes |
|---|:-:|---|
| All combinations | Headings  | All `<h3>` card heading elements not navigable  |
| All combinations | Form Controls | When **Sort By**, **Topic**, **Location**, **When** are collapsed checkbox and radio buttons are not identified  |
