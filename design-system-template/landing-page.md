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
- None
## Future proofing type suggestions
- The `<nav>` landmark and `aria-label` attribute (with a unique name) is missing from the breadcrumb navigation

## Screen reader testing
- Form control navigation using the keys <kbd>F</kbd>, <kbd>B</kbd>, <kbd>X</kbd>, (<kbd>R</kbd> NVDA only)

|   |Screen Reader   | Images | Headings  |Landmarks   |Tables   | Lists |Links |Form Controls |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Edge <sup>v100</sup> 		| JAWS <sup>v2021</sup> 	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  |
| Chrome <sup>v100</sup> 	| JAWS <sup>v2021</sup>  	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  |
| FireFox <sup>v99</sup> 	| JAWS <sup>v2021</sup>   	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:   | :heavy_check_mark:  | :heavy_check_mark:  |
| Edge <sup>v100</sup> 		| NVDA <sup>v2020</sup> 	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark:  |
| Chrome <sup>v100</sup> 	| NVDA <sup>v2020</sup>  	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_minus_sign:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  |
| FireFox <sup>v99</sup> 	| NVDA <sup>v2020</sup>   	| :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_minus_sign:   | :heavy_check_mark:  | :heavy_check_mark:  |:heavy_check_mark:  |
| iOS <sup>v15.3.1</sup> 	| VoiceOver 				| :heavy_check_mark:  | :heavy_check_mark:  | :grey_question:  | :heavy_minus_sign:  | :heavy_check_mark: | :heavy_check_mark:  | :heavy_check_mark:   |
| MacOS <sup>v12.2.1</sup> 	| VoiceOver  				|:heavy_check_mark:  | :heavy_check_mark:   | :grey_question:   | :heavy_minus_sign: | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:  |
| Android <sup>v11</sup> 	| TalkBack 					| :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  | :white_circle:  |

### Observations
|  | Element  | Notes |
|---|:-:|---|
| All combinations | Images  | **Image Block RHS Heading Runs Across 1-2 Lines** 1x image described _img graphic_  |
| All combinations | Images  | **4 column content block with image area** 3x image described as _img graphic_ |
| All combinations | Images  | **The Sea, The Sea, The Glorious Sea…** 2x image described as _img..._  |
| All combinations | Images  | **Campaign quote RHS header runs across 2 or 3 lines** 1x image described as _dss graphic_  |
| All combinations | Headings | **Top**, **Default tag**, **Not sure where to start? Call us on 1300 84 74 66** identify as a headings |
| All combinations | Landmarks | Multiple unnamed navigation landmark regions |
| All combinations | Lists  | Side menu list items are navigable when menu is closed  |
| All combinations | Links  | **Top** unreachable
| All combinations | Links  | **1300 84 74 66** described as _phone no_
|iOS | Links | Navigation appears to become stuck in the card content |
| Chrome, Edge, Firefox NVDA | Links | **News/Blog component with images** 2x image described as _img graphic..._
| All combinations | Form Controls  | YouTube form controls may be difficult to identify for individual videos
