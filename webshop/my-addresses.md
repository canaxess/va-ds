# My Addresses
## WCAG compliance related to 2.1 AA
- **First name, Last name, Address, Mobile number** input labels are not programmatically associated to the controls on **Add new address** dialog
- **Zip/Postal Code** on **Edit address** dialog displays an initial empty inline validation container when opened
- **You saved the address.** message uses an incorrect aria live region role, it should be `role="status"`
## Highly recommended usability suggestions for screen reader users
- none
## Future proofing type suggestions
- **Add new address** dialog has a `<h1>` heading element and should be a `<h2>` to reflect the child content
- consider containing the footer links within the `<nav>` element
- consider the `<title>` text convention of **page name | website name**
