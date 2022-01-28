This code will allow you to serve the official Roof Maxx Consumer Form on your website.

Step One: CSS and JS
===

Using the following URL's, include the CSS and JS files in the head of your page:

CSS:
---

    <link href="https://cdn.jsdelivr.net/gh/roofmaxx/react-form/css/54bfa786.min.css" rel="stylesheet">

JS:
---

    <script type="module" src="https://cdn.jsdelivr.net/gh/roofmaxx/react-form/js/7058a028.js"></script>


Step 2: HTML
---

Add this HTML element wherever you would to see the form on your page:

**Please note: you MUST include a value for data-dealer-id**

EXAMPLE 1:
---

    <div id="roofmaxx-form" data-dealer-id="123456789"></div>

EXAMPLE 2:
---

    <div id="roofmaxx-form" data-dealer-id="123456789" data-source-vendor="" data-thank-you-page=""></div>

EXAMPLE 3:
---

    <div id="roofmaxx-form" data-dealer-id="123456789" data-source-vendor="SM" data-thank-you-page="https://google.com"></div>
