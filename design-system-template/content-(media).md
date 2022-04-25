# CONTENT (MEDIA)
## WCAG compliance related to 2.1 AA
- Links within the body content change colour only when in keyboard focus
- When the menu is open <kbd>Shift</kbd> + <kbd>Tab</kbd> causes the keyboard focus to leave the menu
- Phone number link has `aria-label="phone no"`
- **On this page** side links have no keyboard focus effect

## Highly recommended usability suggestions for screen reader users
- None
## Future proofing type suggestions
- Irregular heading levels applied, a `<h5>`**On this page** followed by `<h2>`**Video Title**
- YouTube video has insufficient title text
- Verbose title text, consider more succinct text

## Screen reader testing
- Form control navigation using the keys <kbd>F</kbd>, <kbd>B</kbd>, <kbd>X</kbd>, (<kbd>R</kbd> NVDA only)

### Legend
- :heavy_check_mark: = Element exists and is applied correctly
- :x: = Element exists and is not applied correctly
- :heavy_minus_sign: = Element does not exist
- :grey_question:= Unclear screen reader behaviour
- :white_circle: = Test not run

|   |Screen Reader   | Images | Headings  |Landmarks   |Tables   | Lists |Links |Form Controls |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v100</sup> 		| JAWS <sup>v2021</sup> 	| :heavy_minus_sign:  | :heavy_check_mark: | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  |
| Chrome <sup>v100</sup> 	| JAWS <sup>v2021</sup>  	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  |
| FireFox <sup>v99</sup> 	| JAWS <sup>v2021</sup>   	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  |
| Edge <sup>v100</sup> 		| NVDA <sup>v2020</sup> 	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark: | :heavy_check_mark:  |
| Chrome <sup>v100</sup> 	| NVDA <sup>v2020</sup>  	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  |
| FireFox <sup>v99</sup> 	| NVDA <sup>v2020</sup>   	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :heavy_minus_sign:  | :heavy_check_mark:  | :grey_question:   | :heavy_minus_sign:   | :heavy_minus_sign:   | :heavy_check_mark:  | :heavy_check_mark:  |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				| :heavy_minus_sign:  | :heavy_check_mark:  | :grey_question:  | :heavy_minus_sign:  |:heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  |
| Android <sup>v11</sup> 	| TalkBack 					| :grey_question:  | :white_circle:  | :white_circle:  | :grey_question:  | :grey_question:  | :white_circle:  | :white_circle:  |

### Observations
|  | Element  | Notes |
|---|:-:|---|
| All combinations | Headings | Unnecessary heading **On this page**
