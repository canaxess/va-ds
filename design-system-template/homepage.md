# HOMEPAGE
## WCAG compliance related to 2.1 AA
- Links within the body content change colour only when in keyboard focus

## Highly recommended usability suggestions for screen reader users
- None

## Future proofing type suggestions
- None
## Screen reader testing
- Form control navigation using the keys <kbd>F</kbd>, <kbd>B</kbd>, <kbd>X</kbd>, (<kbd>R</kbd> NVDA only)

### Legend
- :heavy_check_mark: = Element exists and is applied correctly
- :x: = Element exists and is not applied correctly
- :heavy_minus_sign: = Element does not exist
- :grey_question:= Unclear screen reader behaviour
- :white_circle: = Test not run

|   |Screen Reader   | Images | Headings  |Landmarks   |Tables   | Lists |Links |Form Controls | Side Menu |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v100</sup> 		| JAWS <sup>v2021</sup> 	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  |
| Chrome <sup>v100</sup> 	| JAWS <sup>v2021</sup>  	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark: |
| FireFox <sup>v99</sup> 	| JAWS <sup>v2021</sup>   	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  |
| Edge <sup>v100</sup> 		| NVDA <sup>v2020</sup> 	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_minus_sign:  | :heavy_check_mark:  |
| Chrome <sup>v100</sup> 	| NVDA <sup>v2020</sup>  	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  |
| FireFox <sup>v99</sup> 	| NVDA <sup>v2020</sup>   	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :heavy_check_mark:  | :heavy_check_mark:   | :grey_question:   |  :heavy_minus_sign:   | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :x:  |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				| :heavy_check_mark:  | :heavy_check_mark:  | :grey_question:   | :heavy_minus_sign: | :heavy_check_mark:  | :heavy_check_mark:   | :heavy_minus_sign:  |:x:   |
| Android <sup>v11</sup> 	| TalkBack 					| :grey_question:  | :heavy_check_mark:  | :heavy_check_mark:  |  :heavy_minus_sign:  | :grey_question:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  |

### Observations
|  | Element  | Notes |
|---|:-:|---|
| All combinations | Lists  | Side menu list items are navigable when menu is closed  |
| All combinations | Lists  | Each breadcrumb item is contained in its own landmark `role="navigation"` |
| All combinations | Links  | Unable to tab reach **Contact us** link |
| All combinations | Links  | Side menu links are navigable when menu is closed |
| MacOS, iOS, TalkBack | Headings | **Home page headline line 1 page headline.** are 2 `<h1>` heading elements |
| All combinations | Landmarks  | Vision Australia footer logo is identified as a landmark region |
| Chrome, Edge, MacOS, iOS NVDA | Side Menu | No indication menu has expanded |
| Chrome, Edge, MacOS, iOS JAWS NVDA | Side Menu | No indication sub-menu items have expanded |
| All combinations | Side Menu | Close menu button is described as _times menu link_ |





