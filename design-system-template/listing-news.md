# LISTING NEWS
## WCAG compliance related to 2.1 AA
- Links within the body content change colour only when in keyboard focus
- Dates do not reflow and obscure text content on the cards when WCAG 2.1 AA text spacing requirements are applied
- Phone number link has `aria-label="phone no"`

## Highly recommended usability suggestions for screen reader users

## Future proofing type suggestions
- Irregular heading levels applied, `<h3>` on the cards with no preceeding `<h2>`
- Consider rephrasing the pagination links with the number followed by the ordinal indicator then text _2nd page_, _3rd page_
- Consider applying the `<time>` elements when displaying dates
- Consider wrapping each card element within a `<li>` element
- Consider using an aria-live region with `role="status"` to output when a page has re-sorted

## Screen reader testing
- Form control navigation using the keys <kbd>F</kbd>, <kbd>B</kbd>, <kbd>X</kbd>, (<kbd>R</kbd> NVDA only)

|   |Screen Reader   | Images | Headings  |Landmarks   |Tables   | Lists |Links |Form Controls | Sort & Filter | Pager |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v100</sup> 		| JAWS <sup>v2021</sup> 	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign: | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :white_circle: | :white_circle:
| Chrome <sup>v100</sup> 	| JAWS <sup>v2021</sup>  	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :white_circle: | :white_circle:
| FireFox <sup>v99</sup> 	| JAWS <sup>v2021</sup>   	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :white_circle: | :white_circle:
| Edge <sup>v100</sup> 		| NVDA <sup>v2020</sup> 	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark:  | :white_circle: | :white_circle:
| Chrome <sup>v100</sup> 	| NVDA <sup>v2020</sup>  	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :white_circle: | :white_circle:
| FireFox <sup>v99</sup> 	| NVDA <sup>v2020</sup>   	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :white_circle: | :white_circle:
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle: | :white_circle:
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle: | :white_circle:
| Android <sup>v11</sup> 	| TalkBack 					| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle: | :white_circle:

### Observations
|  | Element  | Notes |
|---|:-:|---|
| Chrome, Edge, FireFox JAWS | Form Controls | When **Topic** is collapsed pressing <kbd>X</kbd> describes _there are no checkboxes on this page_ |
| Chrome, Edge, FireFox NVDA | Form Controls | When **Sort By** is collapsed pressing <kbd>R</kbd> describes _there are no radio buttons on this page_ |
| Chrome, Edge, FireFox JAWS NVDA | Sort | Control collapses and last focus position is lost when **most recent** is selected |
| Chrome, Edge, FireFox JAWS | Sort | Last focus position is lost when **most recent** is selected |
| Edge, FireFox JAWS NVDA | Filter | Control collapses when **19th century authors** is toggled |
| FireFox JAWS | Filter | Last focus position is lost when **19th century authors** is selected |
