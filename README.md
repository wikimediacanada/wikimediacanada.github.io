# 2016 website

## Overview
This repository is the transaction portion of the website updated in fall 2016.

The purpose of this website is to provide an area outside the [www.wikimedia.ca](http://www.wikimedia.ca) wiki for Paypal transactions such as joining the organization or making a donation.

Originally authored by Jeffery Nicholls, the site was rewritten by David Fourney.

**The following major changes were made:**

* The folders containing the original Paypal button graphics were removed.
* Code was updated to HTML5.
* All styling, including buttons, was moved to a CSS stylesheet `wmca.css`.
* Language information was added to each page:
  * `lang` tags added as appropriate
  * `charset` to Unicode (utf-8)
  * `hreflang` links added to support SEO
  * a link to the French/English equivalent added
* Form code originally provided by Paypal was made accessible:
   * labels properly associated with inputs
* Buttons were made accessible:
  * higher contrast of text from background using CSS
  * keyboard accessible `focus` state
  * mouse accessible `hover` state
  * Button `alt` text was updated to reflect the button's purpose. (The "Join" and "Donate" buttons could now be distinguished by non-visual users.)
* Updated content and corrected translations.

This site was replaced in the summer of 2017 (see **master** branch).
