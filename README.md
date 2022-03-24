# AliExpress Invoice Generator 2021

This is a browser extension for generating PDF invoices on [AliExpress] website.

2022 BigJonMMXX - Aliexpress now has a "Download Invoice" on the "Order Details" page. But... 
1) its a pain to open every order to press this button - so i want a buttons on Summary page.
2) it defaults to postal-address which is not always company tax address.
3) couldnt enter tax code onto invoice
4) original plugin has been replaced with a broken plugin :(

Based on open source project by Johannes Marbach using pdfkit - "At the time of implementing this, AliExpress didn't offer any downloadable
invoice format. Existing add-ons were closed source and looked rather phishy so I decided
to write my own. I originally developed this add-on for my personal needs only. Many of
the current features were added later, motivated by an ever growing user base and helpful
feedback from like-minded people."

Key features:
- _Free_ - this plugin does not cost you any money
- _Free_ - The code is open source. uou can modify. you can use it. But you have to agree to the GPLv3 (or later).
- _Zero tracking_ - No tracking, no recording, no analytics, no network requests, no nothing !!
- _Secure_ - Code is open source, you can see it all. 

![](screenshots/statistics.png "Firefox user statistics")

A few screenshots:

![](screenshots/onboarding-1.png "Two ways to create the invoice")

![](screenshots/onboarding-2.png "Generated PDF")

![](screenshots/onboarding-3.png "Extension settings")

## Installing

You can install the extension directly from the official [addons.mozilla.org] website
or from the [Chrome Web Store].

## Running (from Code)

For development and testing you can run the extension from code in an isolated browser
instance using the following commands:

1. Initialize the plugin (only once):

```
npm install
npm run init
```

2. Build or serve the plugin using the following commands: `npm run serve` or `npm run build`.

## License

AliExpress Invoice Generator is licensed under the GNU General Public License as published
by the Free Software Foundation, either version 3 of the License, or (at your option) any
later version.

[PDFKit] is distributed under the MIT license.

The Droid Sans fonts are distributed under the Apache license.

[AliExpress]: https://www.aliexpress.com
[addons.mozilla.org]: https://addons.mozilla.org/firefox/addon/aliexpress-invoice-generator/
[Chrome Web Store]: https://chrome.google.com/webstore/detail/haebneihcbnfnhbdpokdbkekepnoiadn
[PDFKit]: https://github.com/foliojs/pdfkit
