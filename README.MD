This code will allow you to serve the official Roof Maxx Consumer Form on your website.
Requests submitted through this form will go into Hubspot, and then on to Client Tether and Dispatch.

If you need any assistance, please contact techsupport-at-roofmaxx-dot-com or marketing-at-roofmaxx-dot-com.

*Please note that as of January 2022, this is experimental and likely to change. Please check back often for updates and keep in touch with us to be sure you have the most current version.*


Installation Instructions
===

Step One: CSS and JS
===

Include the CSS and JS files in the head of your page:


CSS:
---

    <link href="https://cdn.jsdelivr.net/gh/roofmaxx/react-form/css/54bfa786.min.css" rel="stylesheet">

JS:
---

    <script type="module" src="https://cdn.jsdelivr.net/gh/roofmaxx/react-form/js/7058a028.js"></script>


Step 2: HTML
===

Add this HTML element wherever you would to see the form on your page:

**Please note: you MUST include a value for data-dealer-id**

EXAMPLE 1:
---
A minimal example with a "dealer ID".  (If it isn't obvious, please note that you need to use your dealership's actual dealer ID here, not `123456789`)

    <div id="roofmaxx-form" data-dealer-id="123456789"></div>

EXAMPLE 2:
---
Same result as above, but we're explicitly passing empty values through for 'source vendor' and 'thank-you-page'

    <div id="roofmaxx-form" data-dealer-id="123456789" data-source-vendor="" data-thank-you-page=""></div>

EXAMPLE 3:
---
In this example, we are explicitly defining a 'source_vendor' and a 'thank-you-page'
This will not apply for most dealers, but some vendors may be able to use the 'source_vendor' feature.
If the thank-you data is left empty or omitted, the default is `https://roofmaxx.com/thank-you`

    <div id="roofmaxx-form" data-dealer-id="123456789" data-source-vendor="SG" data-thank-you-page="https://roofmaxxofsomewhere.com/thank-you"></div>
