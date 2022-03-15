## Footer Design
### WCAG compliance related to 2.1 AA
* remove `tabindex=0` from heading elements (Customer service, About, Get in touch)
* add button element within all heading elements (Customer service, About, Get in touch)
* add `aria-expanded="false"` to button element, toggle value (`true|false`) when button is clicked
* Footer logo links have insufficient change on focus. An outline or border may be appropriate 
* when text spacing accessibility dimensions are applied the social media icon containers do not accommodate the increase consistently.<sup>[1](https://github.com/canaxess/va-ds/edit/main/FOOTER-DESIGN-VA3-T292.md#1-steps-to-reproduce-text-spacing-issue)</sup>

### Highly recommended usability suggestions
* suggestion would be to make the link text clearly describe where the link goes – whether that is the VA web store home, or going to the VA website

### Future proofing suggestion
* add `aria-controls="customerservice"` to button element
* add `id="customerservice"` to related `<ul>` element
* add `aria-controls="about"` to button element
* add `id="about"` to related `<ul>` element
* add `aria-controls="getintouch"` to button element
* add `id="getintouch"` to related `<ul>` element

Status : **incomplete**

### <sup>1</sup> steps to reproduce text spacing issue
1. visit https://html5accessibility.com/tests/tsbookmarklet.html
1. drag "Text Spacing" bookmarklet to address bar
1. click bookmarklet on VA webpage

