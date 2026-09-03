# Live Terpene Viewer

This project is a **client-side HTML/JavaScript web app** that displays **live terpene data** for multiple Florida cannabis brands, currently **Cookies Florida** and **Jungle Boys Florida**.
It’s designed to make terpene information easy to browse, sort, and understand - whether you’re a patient, a dispensary employee, or just curious about what’s in your products.

## Features

* **Live product fetching** from each brand’s public API

  * Cookies Florida: vapes, concentrates, pre-rolls, premium flower
  * Jungle Boys Florida: AIO vapes, concentrates, pre-rolls, premium flower, pops
* **Dynamic sortable tables** with:

  * Product images
  * Prices
  * Product names (clickable, links to the store page for the selected location)
  * Delivery type / subcategory
  * Individual terpene percentages
* **Terpene info icons**

  * Click the ℹ️ icon in any terpene column header to see details on aroma, effects, and potential benefits
* **Hover highlighting** for both rows and columns
* **Progress bar** while loading data
* **Responsive design** for desktop and mobile
* **Optional category filter** to quickly switch between product types

## Data Sources

* **Cookies Florida API**:
  `https://cookiesflorida.co/wp-json/dovetail-api/v1/products`
* **Jungle Boys Florida API**:
  `https://jungleboysflorida.com/wp-json/dovetail-api/v1/products`

### Categories Queried

* **Cookies Florida**

  * `vapes`
  * `concentrates`
  * `pre-rolls`
  * `premium-flower`
* **Jungle Boys Florida**

  * `vape-pens` *(AIO only, no cartridges)*
  * `concentrates`
  * `pre-rolls`
  * `premium-flower`
  * `pops`

## Tech Stack

* **HTML**, **CSS**, **JavaScript**
* No external frameworks or build tools
* Runs entirely in the browser

## How to Use

1. Clone or download this repository
2. Open `index.html` in your browser
3. Choose a brand from the homepage
4. Select your location from the tile grid
5. Browse and sort terpene data for your selected store

### Example:

```
index.html?retailer=jungle-boys-tampa
index.html?retailer=tampa
```

## Terpene Info

Clicking the ℹ️ icon in a terpene column shows a description that may include:

* Common aromas and flavors
* Possible effects
* Potential health-related notes

## Customization Ideas

* Add more brands and categories
* Allow saving favorite strains
* Export terpene tables to CSV
* Add user preference storage with `localStorage`

---

**Note:** All brand logos and product imagery are the property of their respective owners - *Cookies* and *Jungle Boys*. This site is an independent project and not affiliated with either company.

Made with 💙 by [BurlyVik]
