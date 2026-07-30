 Google Search Clone

This project is a front-end implementation of Google Search, Google Image Search, and Google Advanced Search.

 Project Pages

The website contains three pages:

* Google Search** — `index.html`
* Google Image Search** — `images.html`
* Google Advanced Search** — `advanced.html`

 Features
* Google-style search page
* Centered and rounded search bar
* Google Search button
* “I’m Feeling Lucky” button
* Google Image Search
* Google Advanced Search
* Navigation links between all pages
* Four Advanced Search fields:
  * All these words
  * This exact word or phrase
  * Any of these words
  * None of these words
* Responsive design for desktop and mobile devices
* Google-style user interface created using CSS

 Technologies Used
* HTML5
* CSS3
* Google Search GET parameters

 Project Structure
 
text
Project/
│
├── index.html
├── images.html
├── advanced.html
├── styles.css
└── README.md

How to Run:
1. Download or clone this repository.
2. Open the project folder.
3. Double-click `index.html`.
4. The website will open in your web browser.

You can also open the project using Visual Studio Code and the Live Server extension.

Search Functionality:
The regular Google Search page sends the user's search query to:

text:
https://www.google.com/search

The search input uses:
html
name="q"

The Google Image Search page uses:

html
<input type="hidden" name="tbm" value="isch">

The Advanced Search page uses the following Google search parameters:

* `as_q` — all these words
* `as_epq` — this exact word or phrase
* `as_oq` — any of these words
* `as_eq` — none of these words

Author:
Lahari Thota

Project Status:
Completed
