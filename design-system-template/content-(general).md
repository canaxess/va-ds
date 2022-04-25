# CONTENT (GENERAL)
## WCAG compliance related to 2.1 AA
- A HTML table is used on the embedded Google Maps for presentation purposes without the semantics being suppressed
- Links within the body content change colour only when in keyboard focus
- Google Map has no iframe title text
- When the menu is open <kbd>Shift</kbd> + <kbd>Tab</kbd> causes the keyboard focus to leave the menu
- Table cell column **URL of Row** links use an icon and have no link text
- **On this page** side links have no keyboard focus effect

## Highly recommended usability suggestions for screen reader users

## Future proofing type suggestions
- Irregular heading levels applied, a `<h5>` **On this page** follows a `<h1>`
- Several false positive HTML syntax errors identified
- Verbose title text, consider more succinct text

## Screen reader testing
- Form control navigation using the keys <kbd>F</kbd>, <kbd>B</kbd>, <kbd>X</kbd>, (<kbd>R</kbd> NVDA only)

|   |Screen Reader   | Images | Headings  |Landmarks   |Tables   | Lists |Links |Form Controls | Accordion
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v100</sup> 		| JAWS <sup>v2021</sup> 	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  |
| Chrome <sup>v100</sup> 	| JAWS <sup>v2021</sup>  	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  |
| FireFox <sup>v99</sup> 	| JAWS <sup>v2021</sup>   	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  |
| Edge <sup>v100</sup> 		| NVDA <sup>v2020</sup> 	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark:  | :heavy_check_mark: |
| Chrome <sup>v100</sup> 	| NVDA <sup>v2020</sup>  	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: |
| FireFox <sup>v99</sup> 	| NVDA <sup>v2020</sup>   	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle: |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				| :heavy_check_mark:  | :heavy_check_mark:  | :grey_question:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:   | :x: |
| Android <sup>v11</sup> 	| TalkBack 					| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle: |

### Observations
|  | Element  | Notes |
|---|:-:|---|
| All combinations | Images | Unnecessary `ALT` text on 2x image **Embedded Map**, **Embedded Map 2** described as _View Google map graphic_, _Share location graphic_
| All combinations | Images | **Download Program** 1x image described as _publication image graphic_
| All combinations | Images | **Media 1x image** described as _test graphic_
| All combinations | Images | **Campaign images LHS header runs across 2 Or 3 lines** 2x image described as _img graphic_
| All combinations | Headings | 5x instances of the text **text summary** as a heading
| Chrome, Edge JAWS & NVDA | Tables | 2x instances of tables used for layout on Google Maps widget
| All combinations | Form Controls | YouTube and Google Maps form controls may be difficult to identify for individual videos and maps
| Chrome JAWS | Landmarks | 2x Google Maps are contained in an unusually described landmark region _847 map_, _890 map_
| All combinations | Links | Unclear link text in table rows described as _sad_, _sd_, _sada_, _asd_
| MacOS VoiceOver | Accordion | Collapsed and expanded not conveyed by the screen reader |
