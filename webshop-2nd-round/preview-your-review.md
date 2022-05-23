# Screen reader testing
- Form control navigation using the keys <kbd>F</kbd>, <kbd>B</kbd>, <kbd>X</kbd>, (<kbd>R</kbd> NVDA only)
- Within TalkBack the swipe up, then down gesture is used to cycle through the elements **Links**, **Headings**, **Landmarks**, **Controls**

## Legend
- :heavy_check_mark: = Element exists and is applied correctly
- :x: = Element exists and is not applied correctly
- :heavy_minus_sign: = Element does not exist
- :grey_question:= Unclear screen reader behaviour
- :white_circle: = Test not run

|   |Screen Reader   | Images | Headings  |Landmarks   |Tables   | Lists |Links |Form Controls |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v101</sup> 		| JAWS <sup>v2021</sup> 	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign: | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  |
| Chrome <sup>v101</sup> 	| JAWS <sup>v2021</sup>  	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark: |
| FireFox <sup>v100</sup> 	| JAWS <sup>v2021</sup>   	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  |
| Edge <sup>v101</sup> 		| NVDA <sup>v2020</sup> 	| :heavy_minus_sign:  | :heavy_check_mark: | :heavy_minus_sign:  | :grey_question:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark:  |
| Chrome <sup>v101</sup> 	| NVDA <sup>v2020</sup>  	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign: | :grey_question: | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  |
| FireFox <sup>v100</sup> 	| NVDA <sup>v2020</sup>   	| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign:  |  :heavy_minus_sign:    | :heavy_check_mark:  | :heavy_check_mark:  |:heavy_check_mark:  |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_minus_sign: | :grey_question: | :heavy_check_mark:  | :heavy_check_mark:    |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				|:heavy_minus_sign:   | :heavy_check_mark:   | :grey_question:   | :heavy_minus_sign: | :grey_question:   | :heavy_check_mark:   | :heavy_check_mark:  |
| Android <sup>v11</sup> 	| TalkBack 					| :grey_question:  | :x:  | :heavy_minus_sign: | :grey_question:  | :grey_question:  |:heavy_check_mark:  | :heavy_check_mark: |

## Observations
|  | Element  | Notes |
|---|:-:|---|
| All combinations | Lists  | List contains 1 item only  |
| All combinations | Lists  | List announced as "percent of today" due to `<span>` with attribute `itemprop="ratingValue"`  |
| Edge, Chrome NVDA | Tables | Initial identification of table on ratings |
iOS, MacOS VoiceOver | Lists | Lists not found when navigating via list elements on Rotor |
Android TalkBack | Headings | Blank `<h2>` identified after **Preview your review** |
Android TalkBack | Form Controls | Entire main content area highlighted when navigating in Controls mode |
