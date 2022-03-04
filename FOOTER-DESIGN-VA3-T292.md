# Footer Design
* remove `tabindex=0` from heading elements (Customer service, About, Get in touch)
* add button element within all heading elements (Customer service, About, Get in touch)
* add `aria-expanded="false"` to button element, toggle value (`true|false`) when button is clicked
* add `aria-controls="customerservice"` to button element
* add `id="customerservice"` to related `<ul>` element
* add `aria-controls="about"` to button element
* add `id="about"` to related `<ul>` element
* add `aria-controls="getintouch"` to button element
* add `id="getintouch"` to related `<ul>` element

Status : **incomplete**

---

* when text spacing accessibility dimensions are applied the social media icon containers do not accommodate the increase consistently.

**steps to reproduce**
1. visit https://html5accessibility.com/tests/tsbookmarklet.html
1. drag "Text Spacing" bookmarklet to address bar
1. click bookmarklet on VA webpage
