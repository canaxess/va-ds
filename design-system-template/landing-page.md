# LANDING PAGE
## WCAG compliance related to 2.1 AA
- Incorrect ALT text of `dss` on image background quote to **Stella, Vision Australia client**
- Incorrect ALT text of `img` on image background quote to **The Sea, The Sea, The Glorious Sea….** x2
- Incorrect ALT text of `img` on all images **4 column content block with image area**
- Incorrect ALT text of `img` on all images **Navigation card block heading is 1-2 lines**
- Incorrect ALT text of `img` on accompanying image **Image Block RHS Heading Runs Across 1-2 Lines**
- Dates and titles do not reflow and obscure text content on the cards **News/Blog component with images**, **News/Blog component no images**, **Events Component with no images** when WCAG 2.1 AA text spacing requirements are applied
- Heading level of `<h5>` is applied to **Default tag** where no new content is introduced
- YouTube video at **Video block RHS heading is 1-2 lines** has insufficient iframe `title` text of **Youtube Video 2**
- When the menu is open <kbd>Shift</kbd> + <kbd>Tab</kbd> causes the keyboard focus to leave the menu
- Phone number link has `aria-label="phone no"`
- **View transcript** and **share this video** links are unclear
- Side menu does not follow aria authoring practices and contains no `aria-expanded="true|false"` attribute
- Links within the body content change colour only when in keyboard focus
- Desktop menu expand link has no accessible name

## Highly recommended usability suggestions for screen reader users

## Future proofing type suggestions
- The `<nav>` landmark and `aria-label` attribute (with a unique name) is missing from the breadcrumb navigation

## Screen reader testing
|   |Screen Reader   | Images | Headings  |Landmarks   |Tables   | Lists |Links |Form Controls |Complex Controls |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v100</sup> 		| JAWS <sup>v2021</sup> 	| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |
| Chrome <sup>v100</sup> 	| JAWS <sup>v2021</sup>  	| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |
| FireFox <sup>v99</sup> 	| JAWS <sup>v2021</sup>   	| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |
| Edge <sup>v100</sup> 		| NVDA <sup>v2020</sup> 	| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |
| Chrome <sup>v100</sup> 	| NVDA <sup>v2020</sup>  	| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |
| FireFox <sup>v99</sup> 	| NVDA <sup>v2020</sup>   	| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |
| Android <sup>v11</sup> 	| TalkBack 					| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |
