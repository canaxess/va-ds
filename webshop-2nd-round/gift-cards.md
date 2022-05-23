# Screen reader testing
- Form control navigation using the keys <kbd>F</kbd>, <kbd>B</kbd>, <kbd>X</kbd>, (<kbd>R</kbd> NVDA only)

## Legend
- :heavy_check_mark: = Element exists and is applied correctly
- :x: = Element exists and is not applied correctly
- :heavy_minus_sign: = Element does not exist
- :grey_question:= Unclear screen reader behaviour
- :white_circle: = Test not run

|   |Screen Reader   | Images | Headings  |Landmarks   |Tables   | Lists |Links |Form Controls |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v101</sup> 		| JAWS <sup>v2021</sup> 	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  |
| Chrome <sup>v101</sup> 	| JAWS <sup>v2021</sup>  	| :heavy_minus_sign:  |:heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  |
| FireFox <sup>v100</sup> 	| JAWS <sup>v2021</sup>   	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  |
| Edge <sup>v101</sup> 		| NVDA <sup>v2020</sup> 	| :heavy_minus_sign: | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  |
| Chrome <sup>v101</sup> 	| NVDA <sup>v2020</sup>  	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign: | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:  |
| FireFox <sup>v100</sup> 	| NVDA <sup>v2020</sup>   	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:   | :heavy_check_mark:   | :heavy_check_mark:   |:heavy_check_mark:  |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :grey_question: | :heavy_check_mark:  | :heavy_check_mark:   |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				|:heavy_minus_sign:  | :heavy_check_mark:  | :grey_question:  | :heavy_minus_sign: | :grey_question:   | :heavy_check_mark:  | :heavy_check_mark:  |
| Android <sup>v11</sup> 	| TalkBack 					| :grey_question:  | :heavy_check_mark:  | :heavy_minus_sign: | :grey_question:  | :grey_question:  |:heavy_check_mark:  | :heavy_check_mark:  |

## Observations
|  | Element  | Notes |
|---|:-:|---|
iOS, MacOS VoiceOver | Lists | Lists not found when navigating via list elements on Rotor |

