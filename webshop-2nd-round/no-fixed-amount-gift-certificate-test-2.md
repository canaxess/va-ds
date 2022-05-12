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
| Edge <sup>v100</sup> 		| JAWS <sup>v2021</sup> 	| :grey_question:  | :heavy_check_mark:  | :white_circle:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :white_circle:  |
| Chrome <sup>v100</sup> 	| JAWS <sup>v2021</sup>  	| :x:  | :heavy_check_mark:  | :white_circle:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark: | :white_circle:  |
| FireFox <sup>v99</sup> 	| JAWS <sup>v2021</sup>   	| :x: | :heavy_check_mark:  | :white_circle:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :white_circle:  |
| Edge <sup>v100</sup> 		| NVDA <sup>v2020</sup> 	| :x:  | :heavy_check_mark:  | :white_circle:  | :heavy_minus_sign:  | :heavy_check_mark:  | :white_circle: | :white_circle:  |
| Chrome <sup>v100</sup> 	| NVDA <sup>v2020</sup>  	| :x:  | :heavy_check_mark:  | :white_circle: | :heavy_minus_sign:  | :heavy_check_mark:  | :white_circle:  | :white_circle:  |
| FireFox <sup>v99</sup> 	| NVDA <sup>v2020</sup>   	| :x:  | :heavy_check_mark:  | :white_circle:  | :heavy_minus_sign:   | :heavy_check_mark:  | :white_circle:  |:white_circle:  |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle: | :white_circle:  | :white_circle:   |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				|:white_circle:  | :white_circle:   | :white_circle:   | :white_circle: | :white_circle:   | :white_circle:   | :white_circle:  |
| Android <sup>v11</sup> 	| TalkBack 					| :white_circle:  | :white_circle:  | :white_circle: | :white_circle:  | :white_circle:  |:white_circle:  | :white_circle:  |

### Observations
|  | Element  | Notes |
|---|:-:|---|
| All combinations | Images  | An `img` element with missing `ALT` attribute exists  |
| Edge + JAWS | Images  | "There are no graphics on this page" even though an `img` element with missing `ALT` attribute exists  |
| FireFox + JAWS | Images  | "Default slash small underline image graphic" on `img` element with missing `ALT` attribute exists  |
| Edge, FireFox + NVDA | Images  | "No next graphic" even though an `img` element with missing `ALT` attribute exists  |
| Edge, Chrome + JAWS | Links  | **Login**, **Cart** are announced  |
