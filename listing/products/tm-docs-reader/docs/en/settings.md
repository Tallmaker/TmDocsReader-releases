---
title: Settings
---

Select the reader while editing a sheet to open its property panel. The sections below follow the panel order.

## Docs reader

### Product

Choose **All installed products** or a named Tallmaker product from the list. The default is **All installed products**: the reader opens the product list, and search covers installed products that include docs.

Choose one product for a dedicated help sheet. This locks browsing and search to that product and skips the product list. A product must be installed with docs to be readable; choosing its name does not install it.

### Start page (product/page)

Choose the page to open first. The default is empty: the reader opens the product list, or the selected product's first page when **Product** is set to one product.

Enter a product and page separated by a slash, for example `tm-docs-reader/settings`. Use this when a help sheet should open at a particular topic. A product alone, such as `tm-docs-reader`, opens that product's first page. Page names must match the product's docs; a missing page falls back to that product's first page.

When **Product** locks the reader to one product, the start page must belong to that same product. A start page for another product is ignored. Clear the field to return to the usual opening view.

## Appearance

Qlik provides the standard appearance controls for the sheet object, including its title, background and general presentation. The available controls, values and defaults depend on your Qlik Sense version and app theme; the reader adds no appearance settings of its own.

Use these controls when the help sheet needs a clearer title or a presentation that matches the rest of your app. Keep enough contrast and space for comfortable reading.

## About

### Product information

Shows the reader's name and installed version, that it is free and needs no licence, and that Tallmaker AS publishes it. This is read-only information with no value to change. Check it when you need to know which reader version you are using.

### Tm Docs Reader link

Opens the reader's page on the Tallmaker website. It is a fixed link with no setting to change.
