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
| Edge <sup>v100</sup> 		| JAWS <sup>v2021</sup> 	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_minus_sign:  |
| Chrome <sup>v100</sup> 	| JAWS <sup>v2021</sup>  	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_minus_sign:  |
| FireFox <sup>v99</sup> 	| JAWS <sup>v2021</sup>   	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign: | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_minus_sign: |
| Edge <sup>v100</sup> 		| NVDA <sup>v2020</sup> 	| :heavy_check_mark:   | :heavy_check_mark:   | :heavy_minus_sign:  | :heavy_minus_sign: | :heavy_check_mark:  | :heavy_check_mark: | :heavy_minus_sign:  |
| Chrome <sup>v100</sup> 	| NVDA <sup>v2020</sup>  	| :heavy_check_mark:   | :heavy_check_mark:   | :heavy_minus_sign: | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_minus_sign:   |
| FireFox <sup>v99</sup> 	| NVDA <sup>v2020</sup>   	| :heavy_check_mark:   | :heavy_check_mark:   | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  |:heavy_minus_sign:   |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :grey_question: | :heavy_check_mark: | :heavy_minus_sign:  |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				| :heavy_check_mark:  |  :heavy_check_mark:   | :heavy_minus_sign:   | :heavy_minus_sign: | :grey_question:   | :heavy_check_mark:   | :heavy_minus_sign: |
| Android <sup>v11</sup> 	| TalkBack 					| :white_circle:  | :white_circle:  | :white_circle: | :white_circle:  | :white_circle:  |:white_circle:  | :white_circle:  |

### Observations
|  | Element  | Notes |
|---|:-:|---|
| All combinations | Lists  | Single list item identified on **Tactile Puzzle Cube - Modified for the Blind** image |
iOS, MacOS VoiceOver | Lists | Lists not found when navigating via list elements on Rotor |
